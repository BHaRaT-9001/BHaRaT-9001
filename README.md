<h1 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=28&duration=3000&pause=1000&color=00FF00&background=000000&center=true&vCenter=true&width=600&lines=%3E+whoami;Full-Stack+Developer;%3E+cat+skills.txt;JavaScript+%7C+React+%7C+Node.js;%3E+status+--online" alt="Typing SVG" />
</h1>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:000000,100:00FF00&height=180&section=header&text=WELCOME%20TO%20MY%20TERMINAL&fontSize=35&fontColor=00FF00&animation=fadeIn&fontAlignY=38" />
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=yourusername&label=TERMINAL+VISITS&color=00FF00&style=for-the-badge&labelColor=000000" alt="visitor count"/>
</p>

---

### `$ ./run.sh --intro`

```bash
> Initializing developer_profile.exe...
> Loading modules: [passion, curiosity, caffeine] ... DONE
> Name       : Your Name
> Role       : Software Developer
> Stack      : JavaScript / React / Node.js
> Status     : Building things that (usually) don't break production
> Fun fact   : I debug with console.log() and I'm not ashamed
```

<br>

<table align="center">
<tr>
<td valign="top" width="50%">

### `$ cat about_me.md`

```yaml
🔭 Currently working on: something cool, probably
🌱 Currently learning:  new frameworks & best practices
👯 Looking to collaborate on: open source projects
💬 Ask me about:        React, Node.js, JS ecosystem
⚡ Fun fact:             this README has a snake game
```

</td>
<td valign="top" width="50%">

### `$ ./connect.sh`

<a href="https://linkedin.com/in/yourusername" target="_blank">
  <img src="https://img.shields.io/badge/LinkedIn-000000?style=for-the-badge&logo=linkedin&logoColor=00FF00" />
</a>
<br><br>
<a href="mailto:youremail@example.com">
  <img src="https://img.shields.io/badge/Email-000000?style=for-the-badge&logo=gmail&logoColor=00FF00" />
</a>

</td>
</tr>
</table>

---

### `$ ls -la ./tech_stack/`

<p align="center">
  <img src="https://skillicons.dev/icons?i=js,ts,react,nodejs,express,html,css,tailwind,mongodb,postgres,git,github,docker,vscode,figma,npm&theme=dark" />
</p>

---

### `$ ./stats.sh --github`

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=yourusername&show_icons=true&theme=github_dark_dimmed&hide_border=true&bg_color=000000&title_color=00FF00&icon_color=00FF00&text_color=ffffff" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=yourusername&layout=compact&theme=github_dark_dimmed&hide_border=true&bg_color=000000&title_color=00FF00&text_color=ffffff" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=yourusername&theme=github-dark-blue&hide_border=true&background=000000&stroke=00FF00&ring=00FF00&fire=00FF00&currStreakLabel=00FF00" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=yourusername&bg_color=000000&color=00FF00&line=00FF00&point=ffffff&area=true&hide_border=true" />
</p>

---

### `$ ./run_game.sh --name=snake --fuel=commits`

<p align="center">
  <img src="[https://raw.githubusercontent.com/yourusername/yourusername/output/github-contribution-grid-snake-dark.svg](https://raw.githubusercontent.com/BHaRaT-9001/BHaRaT-9001/refs/heads/output/github-contribution-grid-snake-dark.svg)" alt="snake eating contribution graph" />
</p>

> The snake above eats through my real contribution graph — every green square is a commit. 🐍

<details>
<summary><b>⚙️ How to make the snake work on your own README (click to expand)</b></summary>

<br>

1. Create a new repo named exactly the same as your GitHub username (e.g. `yourusername/yourusername`).
2. Add this GitHub Action workflow file at `.github/workflows/snake.yml`:

```yaml
name: Generate Snake

on:
  schedule:
    - cron: "0 */6 * * *"
  workflow_dispatch: {}
  push:
    branches: [ main ]

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk/svg-only@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - name: push snake svg to output branch
        uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

3. Push it — the Action generates the snake SVG on a schedule and commits it to an `output` branch.
4. Point the `<img>` src above at:
   `https://raw.githubusercontent.com/<you>/<you>/output/github-contribution-grid-snake-dark.svg`

That's it — the snake now "eats" your real commit history automatically.

</details>

---

### `$ ./quote.sh --random`

<p align="center">
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=radical" />
</p>

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:00FF00,100:000000&height=100&section=footer" />
</p>

<p align="center">
  <i>💻 "Code never lies, comments sometimes do."</i>
</p>
