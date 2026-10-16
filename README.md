<!-- Troque Mateusds pelo seu usuário do GitHub. Os SVGs ficam em assets/ no mesmo repositório. -->

<img src="hero.svg" alt="Mateus Marques — Desenvolvedor Full Stack" width="100%"/>

<br/><br/>

<img src="sec-faco.svg" alt="O que eu faço" width="100%"/>

<img src="cards.svg" alt="Chatbots, verificação facial, telemedicina, dashboards, infra e redesign" width="100%"/>

<br/>

<img src="sec-stack.svg" alt="Stack" width="100%"/>

<img src="stack.svg" alt="Tecnologias que uso" width="100%"/>

<br/>

<img src="sec-atividade.svg" alt="Atividade" width="100%"/>

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Mateusds&show_icons=true&hide_border=false&bg_color=0d1320&border_color=1e2a44&title_color=4f8cff&icon_color=22d3ee&text_color=9fb0d0&border_radius=14" height="170" alt="GitHub stats"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Mateusds&layout=compact&bg_color=0d1320&border_color=1e2a44&title_color=4f8cff&text_color=9fb0d0&border_radius=14" height="170" alt="Linguagens mais usadas"/>

<img src="https://raw.githubusercontent.com/Mateusds/Mateusds/output/github-contribution-grid-snake-dark.svg" alt="Contribuições" width="100%"/>

</div>

<br/>

<img src="sec-contato.svg" alt="Contato" width="100%"/>

<img src="footer.svg" alt="Vamos construir algo juntos?" width="100%"/>

<div align="center">

<a href="https://www.linkedin.com/in/mateus-marques-a50a19113/"><img src="https://img.shields.io/badge/LinkedIn-0d1320?style=for-the-badge&logo=linkedin&logoColor=4f8cff&labelColor=0d1320&color=1e2a44" alt="LinkedIn"/></a>
<a href="mailto:mateusmarquesds@gmail.com"><img src="https://img.shields.io/badge/E--mail-0d1320?style=for-the-badge&logo=gmail&logoColor=22d3ee&labelColor=0d1320&color=1e2a44" alt="E-mail"/></a>
<img src="https://komarev.com/ghpvc/?username=Mateusds&style=for-the-badge&color=1e2a44&labelColor=0d1320&label=VISITAS" alt="Visitas"/>

</div>

<!--
Cobrinha: crie .github/workflows/snake.yml (e rode uma vez em Actions > Run workflow)

name: Generate Snake
on:
  schedule: [{ cron: "0 0 * * *" }]
  workflow_dispatch:
permissions:
  contents: write
jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk/svg-only@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: dist/github-contribution-grid-snake-dark.svg?palette=github-dark
      - uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
-->
