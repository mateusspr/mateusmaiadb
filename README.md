### Olá me chamo Mateus Pereira👋


- 🔭 Trabalho hoje com o Java
- 🎓 Estudando Java/HTML/JavaScript

<div>
  <a href="https://github.com/maeteusmaiadb">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=mateusmaiadb&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=mateusmaiadb&layout=compact&langs_count=7&theme=tokyonight"/>
</div>
  
  <div style="display: inline_block"><br>
  <img align="center" alt="Mateus-Java" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" />
  <img align="center" alt="Mateus-Csharp" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg">
  <img align="center" alt="Mateus-HTML" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg">
  <img align="center" alt="Mateus-CSS" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg">
</div>
  
  ##
  
 <div>
  <a href="https://instagram.com/mateuss.1mao" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
  <a href="https://https://www.linkedin.com/in/mateuspereiamaiaprogrammer/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a> 
   
   
   ![Snake animation](https://github.com/mateusmaiadb/blob/output/github-contribution-grid-snake.svg)
   
   name: Generate Datas

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
          github_user_name: rafaballerini
          svg_out_path: dist/github-contribution-grid-snake.svg

      - uses: crazy-max/ghaction-github-pages@v2.1.3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
   
 </div>
