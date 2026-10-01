# Relatório Estratégico · Araúz

Pacote estático do relatório, pronto para versionamento em Git e publicação no Vercel. O site utiliza HTML, CSS e JavaScript no navegador, com dados locais nas pastas `data/` e `assets/`.

## Publicar no Git

1. Extraia o conteúdo deste pacote na raiz do repositório.
2. Envie `index.html`, `assets/`, `data/` e este `README.md` ao Git.
3. Conecte o repositório ao Vercel.

## Configuração no Vercel

- **Framework Preset:** Other
- **Build Command:** deixe em branco (não há etapa de build)
- **Output Directory:** `.` (raiz do projeto)
- **Root Directory:** raiz do repositório, onde está o `index.html`

A implantação estática do Vercel aceita arquivos HTML/CSS/JavaScript sem build; com o preset Other, a raiz é servida quando não há uma pasta `public`. Consulte a [documentação oficial de configuração de build](https://vercel.com/docs/builds/configure-a-build) e de [builds estáticos](https://vercel.com/docs/builds).

## Estrutura

- `index.html` — relatório e interações
- `assets/` — logo New Lever
- `data/` — dados do relatório, incluindo os arquivos usados nos gráficos e no mapa

Mantenha a estrutura de pastas: o relatório carrega os dados e a logo por caminhos relativos.
