<h1 align="center">👋 Olá! Eu sou o <strong>Vinicius Bariane</strong></h1>

<p align="center">
  <img
    src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=F78C6C&center=true&vCenter=true&width=800&lines=Bem-vindo+ao+meu+GitHub!;Desenvolvedor+focado+em+C%23+e+ASP.NET;Apaixonado+por+aprender+e+compartilhar+conhecimento+🚀"
  />
</p>

---

## 👨‍💻 Sobre mim

- 🎓 **Formação:** Técnico em Desenvolvimento de Sistemas | Engenharia de Computação  
- 💼 **Atuação:** Desenvolvimento com **C# e ASP.NET**  
- ⚙️ **Competências:** C#, ASP.NET, PHP, Java, MySQL  
- 🌐 **Idiomas:** Português (nativo) | Inglês (intermediário)

> Desenvolvedor focado em evolução contínua, boas práticas e soluções que geram impacto real.

---

## 🧰 Tecnologias e Ferramentas

<p align="center">
  <img
    src="https://skillicons.dev/icons?i=cs,dotnet,php,java,spring,mysql,js,react,html,css,git,github,visualstudio,vscode&theme=dark"
  />
</p>

---

## 📊 Estatísticas do GitHub

<p align="center">
  <img
    height="180em"
    src="https://github-readme-stats.vercel.app/api?username=vinisilvabariane&show_icons=true&theme=radical&include_all_commits=true&count_private=true&cache_seconds=86400"
  />
  <img
    height="180em"
    src="https://github-readme-stats.vercel.app/api/top-langs/?username=vinisilvabariane&layout=compact&theme=radical&langs_count=8&cache_seconds=86400"
  />
</p>

<!-- ALTERNATIVA CASO OS STATS ACIMA NÃO FUNCIONEM -->
<!--
<p align="center">
  <img height="180em" src="https://github-stats-alpha.vercel.app/api?username=vinisilvabariane&cc=0a0a0a&tc=fff&ic=fff&bc=000" />
  <img height="180em" src="https://github-readme-stats-git-masterrstaa-rickstaa.vercel.app/api/top-langs/?username=vinisilvabariane&layout=compact&theme=radical" />
</p>
-->

---

## 🐍 Contribution Graph

<!-- IMPORTANTE: Você PRECISA criar o arquivo .github/workflows/snake.yml no seu repositório! 
     Veja as instruções no final deste README ou no comentário abaixo -->

<p align="center">
  <img
    src="https://raw.githubusercontent.com/vinisilvabariane/vinisilvabariane/output/github-contribution-grid-snake.svg"
    alt="Contribution Snake"
  />
</p>

<!-- MENSAGEM DE FALLBACK CASO A COBRINHA AINDA NÃO TENHA SIDO GERADA -->
<p align="center">
  <sub>⚠️ Se a cobrinha não aparecer, aguarde 2-5 minutos após executar o workflow manualmente na aba Actions ⚠️</sub>
</p>

---

## 🌍 Conecte-se comigo

<p align="center">
  <a href="https://www.linkedin.com/in/vinicius-bariane-57a298221/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://www.instagram.com/vini_bariane/" target="_blank">
    <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" />
  </a>
</p>

---

<p align="center">
  <em>“A tecnologia move o mundo, mas aprender constantemente é o que faz a gente crescer.” 🚀</em>
</p>

<!-- ============================================= -->
<!-- INSTRUÇÕES PARA ATIVAR A COBRINHA (NÃO VISÍVEL NO README) -->
<!-- ============================================= -->

<!--

🚨 **INSTRUÇÕES OBRIGATÓRIAS PARA FAZER A COBRINHA FUNCIONAR:**

1. Crie uma pasta chamada `.github/workflows/` no seu repositório

2. Dentro dela, crie um arquivo chamado `snake.yml` com este conteúdo:

```yaml
name: Generate Snake Animation

on:
  schedule:
    - cron: "0 */12 * * *"
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      
      - uses: Platane/snk@v3
        with:
          github_user_name: vinisilvabariane
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
            
      - uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
