<!-- HEADER ANIMADO -->
<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=E34F26&center=true&vCenter=true&width=500&lines=Ol%C3%A1%2C+eu+sou+o+Caio+%F0%9F%91%8B;Estudante+de+Comp.+%7C+Blumenau%2C+SC;Java+%7C+Python+%7C+TypeScript;Const%C3%A2ncia+vence+o+talento." alt="Typing SVG" />
</div>

---

```java
// CaioGomes.java
public class CaioGomes {

    String[] stack     = { "Java", "Python", "TypeScript", "HTML/CSS", "C" };
    String[] databases = { "MySQL", "MariaDB", "Supabase" };
    String   goal      = "Primeira vaga como desenvolvedor Java";
    String   location  = "Blumenau, SC 🌧️";
    String   vibe      = "Café + Código + Música ☕";

    public String filosofia() {
        return "Constância vence o talento.";
    }
}
```

---

### 📊 GitHub Stats

<div align="center">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=eucaiogomes&show_icons=true&theme=tokyonight&hide_border=true&count_private=true"/>
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=eucaiogomes&layout=compact&theme=tokyonight&hide_border=true"/>
</div>

---

### 🐍 Contribuições

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/eucaiogomes/eucaiogomes/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/eucaiogomes/eucaiogomes/output/github-snake.svg" />
    <img alt="github-snake" src="https://raw.githubusercontent.com/eucaiogomes/eucaiogomes/output/github-snake.svg" />
  </picture>
</div>

<details>
<summary>⚙️ Como configurar a cobrinha</summary>

Crie o arquivo `.github/workflows/snake.yml` no seu repositório de perfil:

```yaml
name: Generate Snake

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:

jobs:
  generate:
    runs-on: ubuntu-latest
    permissions:
      contents: write

    steps:
      - uses: Platane/snk/svg-only@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-snake.svg
            dist/github-snake-dark.svg?palette=github-dark

      - uses: peaceiris/actions-gh-pages@v3
        with:
          github_token: ${{ secrets.GITHUB_TOKEN }}
          publish_dir: ./dist
          publish_branch: output
```

</details>

---

### 📬 Contato

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/caio-gomes-8bb741219)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:gcaio98406@gmail.com)

</div>
