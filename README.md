### Hello Amando

- 🔭 Estudante na Força do Odio...
- 🌱 Django  ...
- 🤔 Back End ...
- 💬 Somente Isso ...
  
  [![github](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/DevAmando)
![](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white)

![Amando GitHub stats](https://github-readme-stats.vercel.app/api?username=devamando&show_icons=true&theme=radical)


<div style= "display: inline-block"><br>
<img src="https://external-preview.redd.it/cenas-do-anime-sensual-mahou-shoujo-ni-akogarete-viraliza-v0-wI4wYCXyCBZKm-UHOF6sU3JTNPZpXP4aQxpr23HwrOA.jpg?auto=webp&s=1972826d93e8db8ac87b7e1c3d004a00d47e3a31" alt="Girl in a jacket" width="120" height="120" align = right>
</div>
<picture>
<source media="(prefers-color-scheme: dark)" srcset="github-snake-dark.svg" />
<source media="(prefers-color-scheme: light)" srcset="github-snake.svg" />
<img alt="github-snake" src="github-snake.svg" />
</picture>

me: Generate Datas


on:

schedule: # execute every 12 hours

- cron: "* */12 * * *"

workflow_dispatch:

jobs:

build:

name: Jobs to update datas

runs-on: ubuntu-latest

steps:

# Snake Animation

- uses: Platane/snk@master

id: snake-gif

with:

github_user_name: DevAmando

svg_out_path: dist/github-contribution-grid-snake.svg


- uses: crazy-max/ghaction-github-pages@v2.1.3

with:

target_branch: output

build_dir: dist

env:

GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

[Snake animation](https://github.com/GabrielaZanetti/DevAmando/blob/output/github-contribution-grid-snake.svg)

