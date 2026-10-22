<!--
README de perfil — Renan Marlon
Repositório necessário: renanmacedo-rgb/renanmacedo-rgb
Paleta: azul, azul-claro e preto
-->

<div align="center">

<img
  src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,45:0D47A1,100:58A6FF&height=240&section=header&text=Renan%20Marlon&fontSize=46&fontColor=FFFFFF&fontAlignY=35&desc=Ci%C3%AAncia%20da%20Computa%C3%A7%C3%A3o%20%7C%20Java&descSize=17&descAlignY=57&animation=fadeIn"
  width="100%"
  alt="Banner azul tecnológico de Renan Marlon"
/>

<br/>

<a href="https://github.com/renanmacedo-rgb">
  <img
    src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=3000&pause=1000&color=58A6FF&center=true&vCenter=true&width=700&lines=Estudante+de+Ci%C3%AAncia+da+Computa%C3%A7%C3%A3o;Aprendendo+Java%2C+um+passo+de+cada+vez"
    alt="Animação de texto apresentando Renan Marlon"
  />
</a>

<br/>

<a href="https://github.com/renanmacedo-rgb">
  <img src="https://img.shields.io/badge/GitHub-Perfil-0D1117?style=for-the-badge&logo=github&logoColor=58A6FF" alt="GitHub"/>
</a>
<a href="https://www.instagram.com/renanmarlon_/">
  <img src="https://img.shields.io/badge/Instagram-@renanmarlon__-0D1117?style=for-the-badge&logo=instagram&logoColor=E4405F" alt="Instagram"/>
</a>

</div>

---

## `01` — Sobre mim

Olá! Me chamo **Renan**, sou estudante de **Ciência da Computação** na Universidade Federal Rural do Semi-Árido.

A tecnologia que mais estudo atualmente é o **Java**, mas estou ainda estou buscando a melhor área para mim.

<div align="center">

`COMPUTAÇÃO` &nbsp; • &nbsp; `JAVA` &nbsp; • &nbsp; `APRENDIZADO`

</div>

---

## `02` — Tecnologias

<div align="center">

<img
  src="https://skillicons.dev/icons?i=java&theme=dark"
  width="58"
  alt="Java"
/>

<br/>

<img
  src="https://img.shields.io/badge/Java-Estudos%20e%20pr%C3%A1tica-0D47A1?style=for-the-badge&logo=openjdk&logoColor=FFFFFF"
  alt="Java — estudos e prática"
/>

</div>

---

## `03` — GitHub Stats

<div align="center">

<a href="https://github.com/renanmacedo-rgb">
  <img
    height="170"
    src="https://github-readme-stats.vercel.app/api?username=renanmacedo-rgb&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github"
    alt="Estatísticas do GitHub de Renan Marlon"
  />
</a>

<a href="https://github.com/renanmacedo-rgb">
  <img
    height="170"
    src="https://github-readme-stats.vercel.app/api/top-langs/?username=renanmacedo-rgb&layout=compact&theme=tokyonight&hide_border=true&langs_count=6"
    alt="Linguagens mais utilizadas nos repositórios públicos"
  />
</a>

</div>

<sub>As estatísticas são geradas automaticamente por um serviço externo e dependem dos dados públicos disponíveis no GitHub.</sub>

---

## `04` — Contribution Streak

<div align="center">

<a href="https://github.com/renanmacedo-rgb">
  <img
    src="https://streak-stats.demolab.com?user=renanmacedo-rgb&theme=tokyonight&hide_border=true"
    alt="Sequência de contribuições de Renan Marlon"
  />
</a>

</div>

---

## `05` — Activity Graph

<div align="center">

<a href="https://github.com/renanmacedo-rgb">
  <img
    src="https://github-readme-activity-graph.vercel.app/graph?username=renanmacedo-rgb&bg_color=0D1117&color=58A6FF&line=1F6FEB&point=79C0FF&area=true&hide_border=true"
    width="100%"
    alt="Gráfico de atividade no GitHub"
  />
</a>

</div>

---

## `06` — GitHub Trophies

<div align="center">

<a href="https://github.com/renanmacedo-rgb">
  <img
    src="https://github-profile-trophy.vercel.app/?username=renanmacedo-rgb&theme=algolia&no-frame=true&no-bg=true&margin-w=6&column=4"
    width="100%"
    alt="Conquistas do GitHub"
  />
</a>

</div>

---

## `07` — Snake Contribution

<div align="center">

<p>A animação representa o histórico de contribuições do perfil.</p>

<picture>
  <source
    media="(prefers-color-scheme: dark)"
    srcset="https://raw.githubusercontent.com/renanmacedo-rgb/renanmacedo-rgb/output/github-snake-dark.svg"
  />
  <source
    media="(prefers-color-scheme: light)"
    srcset="https://raw.githubusercontent.com/renanmacedo-rgb/renanmacedo-rgb/output/github-snake.svg"
  />
  <img
    alt="Animação da cobra percorrendo o gráfico de contribuições"
    src="https://raw.githubusercontent.com/renanmacedo-rgb/renanmacedo-rgb/output/github-snake.svg"
    width="100%"
  />
</picture>

</div>

<details>
  <summary><strong>Como ativar a animação com GitHub Actions</strong></summary>

  O README não consegue executar uma GitHub Action sozinho. Para gerar os arquivos da animação, crie o arquivo `.github/workflows/snake.yml` no repositório `renanmacedo-rgb/renanmacedo-rgb` e adicione o conteúdo abaixo.

  ```yaml
  name: Generate Snake

  on:
    schedule:
      - cron: "0 0 * * *"
    workflow_dispatch:
    push:
      branches:
        - main

  permissions:
    contents: write

  jobs:
    generate:
      runs-on: ubuntu-latest

      steps:
        - name: Generate contribution snake
          uses: Platane/snk@v3
          with:
            github_user_name: renanmacedo-rgb
            outputs: |
              dist/github-snake.svg
              dist/github-snake-dark.svg?palette=github-dark

        - name: Publish generated files
          uses: crazy-max/ghaction-github-pages@v4
          with:
            target_branch: output
            build_dir: dist
          env:
            GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
  ```

  Depois, abra a aba **Actions** do repositório e execute o workflow manualmente pela opção **Run workflow**. A animação será exibida quando os arquivos forem publicados na branch `output`. Se o repositório usar outra branch principal, ajuste o nome `main` no gatilho `push`.

  Referência: [Platane/snk — documentação oficial](https://github.com/Platane/snk).

</details>

---

## `09` — Conecte-se comigo

<div align="center">

<a href="https://github.com/renanmacedo-rgb">
  <img
    src="https://img.shields.io/badge/GitHub-renanmacedo--rgb-0D1117?style=for-the-badge&logo=github&logoColor=58A6FF"
    alt="GitHub: renanmacedo-rgb"
  />
</a>

<a href="https://www.instagram.com/renanmarlon_/">
  <img
    src="https://img.shields.io/badge/Instagram-renanmarlon__-0D1117?style=for-the-badge&logo=instagram&logoColor=E4405F"
    alt="Instagram: @renanmarlon_"
  />
</a>

</div>

---

<div align="center">

<img
  src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:0D47A1,100:58A6FF&height=130&section=footer&text=At%C3%A9%20a%20pr%C3%B3xima%20linha%20de%20c%C3%B3digo&fontSize=19&fontColor=FFFFFF&animation=fadeIn"
  width="100%"
  alt="Rodapé azul — Até a próxima linha de código"
/>

<sub>RENAN MARLON · CIÊNCIA DA COMPUTAÇÃO · JAVA</sub>

</div>
