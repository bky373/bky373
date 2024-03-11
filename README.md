<h2> Hi, This is Borahm :) <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="25px"> </h2>

<br/>

[**배움**](https://github.com/bky373/cs-n-programming-study/blob/main/java/1%EC%9E%A5_JVM%EC%9D%80%20%EB%AC%B4%EC%97%87%EC%9D%B4%EA%B3%A0%2C%20%EC%9E%90%EB%B0%94%EC%BD%94%EB%93%9C%EB%8A%94%20%EC%96%B4%EB%96%BB%EA%B2%8C%20%EC%8B%A4%ED%96%89%ED%95%98%EB%8A%94%EA%B0%80.md)과 [**피드백**](https://github.com/next-step/kotlin-blackjack/pull/34)을 즐기는 **백엔드 개발자** 이보람입니다.<br/>
부족한 점이 있다면 **고민**과 [**공부**](https://bky373.github.io/), **피드백 수렴**을 통해 끊임없이 개선해 나갑니다.


### Statistics:

<p align="left">
  <img alt="github_stats" src="https://github-readme-stats.vercel.app/api?username=bky373&hide=stars&show_icons=true&theme=radical" width="380" height="130"/> &nbsp;
  <img alt="top_languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=bky373&layout=compact&theme=radical" height="130">
</p>



### Languages & Tools: 

<p>
  <img alt="java" src="https://img.shields.io/badge/-Java-FF7A59?style=flat-square&logo=java&logoColor=white" />
  <img alt="kotlin" src="https://img.shields.io/badge/-Kotlin-01B3E3?style=flat-square&logo=kotlin&logoColor=white" />
  <img alt="python" src="https://img.shields.io/badge/-Python-5881D8?style=flat-square&logo=python&logoColor=white" />
  <br>
  <img alt="slack" src="https://img.shields.io/badge/-Slack-FF4785?style=flat-square&logo=slack&logoColor=white" />
  <img alt="github" src="https://img.shields.io/badge/-Github-313131?style=flat-square&logo=github&logoColor=white" />
</p>

### Challenging!:

:triangular_flag_on_post: ~~[**Line Wiki**](https://github.com/bky373/line-snipets/#Line-Wiki) : 한 줄 한 줄 공부한 내용을 기록합니다. [**오늘 놓친 한 줄은 돌아오지 않는다!**](https://github.com/bky373/line-snipets/#Line-Wiki)~~   >> [블로깅](https://bky373.github.io/)으로 변경


### About More:

📫 How to reach me : bo373@naver.com <br>
🌱 Also study on :  [Velog](https://velog.io/@bky373/) & [Tstory Blog](https://bky373.tistory.com/) & [GitLab](https://kdt-gitlab.elice.io/bky373) & [bbFactory](https://github.com/bbFactory) 

[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fbky373%2Fhit-counter&count_bg=%23FF4EB6&title_bg=%23555555&icon=&icon_color=%23F934A8&title=toured&edge_flat=true)](https://hits.seeyoufarm.com)

<!--
Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
  --> 


jobs:
generate:
runs-on: ubuntu-latest
timeout-minutes: 10

steps:
  # generates a snake game from a github user (<github_user_name>) contributions graph, output a svg animation at <svg_out_path>
  - name: generate github-contribution-grid-snake.svg
    uses: Platane/snk/svg-only@v3
    with:
      github_user_name: bky373
      outputs: |
        dist/github-contribution-grid-snake.svg
        dist/github-contribution-grid-snake-dark.svg?palette=github-dark

  # push the content of <build_dir> to a branch
  # the content will be available at https://raw.githubusercontent.com/<github_user>/<repository>/<target_branch>/<file> , or as github page
  - name: push github-contribution-grid-snake.svg to the output branch
    uses: crazy-max/ghaction-github-pages@v3.1.0
    with:
      target_branch: output
      build_dir: dist
    env:
      GITHUB_TOKEN: ${{ secrets.GH_TOKEN }}