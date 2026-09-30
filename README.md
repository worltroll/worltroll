<!-- ═══════════════════════════════════════════════════════════════
ТЁМНЫЙ ПОСТПАНК · профиль
Деплой:
1) Публичный репозиторий с именем = твоему нику
2) README.md — в корень, папку assets/ — тоже в корень
3) Замени {user} на ник
4) Змея: см. инструкцию внизу
═══════════════════════════════════════════════════════════════ -->

<div align="center">

<img src="https://raw.githubusercontent.com/{user}/{user}/main/assets/header.png" width="100%" alt="спальный район, сумерки"/>

<br/>

<a href="https://git.io/typing-svg">
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=22&pause=1400&color=8B7FB8&center=true&vCenter=true&width=640&lines=%D1%82%D1%83%D1%82+%D1%82%D0%B2%D0%BE%D1%91+%D0%B8%D0%BC%D1%8F;%D0%BE%D0%BA%D0%BD%D0%B0+%D0%B3%D0%BE%D1%80%D1%8F%D1%82%2C+%D0%BD%D0%BE+%D0%BD%D0%B5+%D0%BC%D0%BD%D0%B5;code+%C2%B7+%D0%B4%D0%BE%D0%B6%D0%B4%D1%8C+%C2%B7+%D1%80%D0%B0%D1%81%D1%81%D0%B2%D0%B5%D1%82" alt="typing" />
</a>

<br/>

```javascript
      панельки уходят в темноту.
   а я остаюсь. коммичу.
```

</div>

---

### 🌫 О себе

<table>
<tr>
<td width="60%" valign="top">

> *«здесь будет твой короткий манифест.
> две-три строчки. без пафоса.
> как письмо, которое никто не прочитает.»*

&nbsp;

- 🌃 **кто:** {кто ты / чем занимаешься}
- 🕯 **стек:** {основной стек}
- 🌧 **сейчас:** {что изучаешь / над чем работаешь}
- 📍 **место:** {город / часовой пояс}

</td>
<td width="40%" align="center" valign="middle">

<img src="https://raw.githubusercontent.com/{user}/{user}/main/assets/girl.png" width="230" alt=""/>

<sub>— тишина на девятом этаже —</sub>

</td>
</tr>
</table>

<div align="center">
<img src="https://raw.githubusercontent.com/{user}/{user}/main/assets/panel.png" width="100%" alt=""/>
</div>

---

### 🛠 Инструменты

<p align="left">
<img src="https://img.shields.io/badge/-{Lang}-0d0d12?style=flat-square&logo={lang}&logoColor=8B7FB8&labelColor=1a1025"/>
<img src="https://img.shields.io/badge/-{Framework}-0d0d12?style=flat-square&logo={framework}&logoColor=8B7FB8&labelColor=1a1025"/>
<img src="https://img.shields.io/badge/-{DB}-0d0d12?style=flat-square&logo={db}&logoColor=8B7FB8&labelColor=1a1025"/>
<img src="https://img.shields.io/badge/-{Tool}-0d0d12?style=flat-square&logo={tool}&logoColor=8B7FB8&labelColor=1a1025"/>
</p>

---

### 🕳 Проекты

|  |  |
| --- | --- |
| 🌑 [**{project-1}**](https://github.com/{user}/{repo-1}) | {одна строка — что это и зачем} |
| 🌘 [**{project-2}**](https://github.com/{user}/{repo-2}) | {одна строка — что это и зачем} |
| 🌗 [**{project-3}**](https://github.com/{user}/{repo-3}) | {одна строка — что это и зачем} |

---

### 📊 Статистика

<div align="center">
<img height="165" src="https://github-readme-stats.vercel.app/api?username={user}&show_icons=true&theme=dark&bg_color=0d0d12&title_color=8B7FB8&text_color=9aa0b4&icon_color=6b5b95&border_color=1a1025" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username={user}&layout=compact&theme=dark&bg_color=0d0d12&title_color=8B7FB8&text_color=9aa0b4&border_color=1a1025" />
<br/>
<img src="https://streak-stats.demolab.com?user={user}&theme=dark&background=0d0d12&ring=8B7FB8&fire=6b5b95&currStreakLabel=8B7FB8&sideLabels=9aa0b4&dates=555c70&border=1a1025" />
</div>

---

### 🐍 Змей из коммитов

<div align="center">
<picture>
<source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/{user}/{user}/output/github-snake-dark.svg" />
<source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/{user}/{user}/output/github-snake.svg" />
<img alt="snake" src="https://raw.githubusercontent.com/{user}/{user}/output/github-snake-dark.svg" />
</picture>
</div>

<details>
<summary>⚙️ как включить змею (один раз)</summary>

Создай в репозитории профиля файл `.github/workflows/snake.yml`:

```yaml
name: snake
on:
  schedule: [{ cron: "0 0 * * *" }]
  workflow_dispatch:
permissions: { contents: write }
jobs:
  snake:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-snake.svg
            dist/github-snake-dark.svg?palette=github-dark
      - uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

</details>

---

<div align="center">

### Связь

<a href="https://t.me/{username}"><img src="https://img.shields.io/badge/Telegram-0d0d12?style=flat-square&logo=telegram&logoColor=8B7FB8&labelColor=1a1025"/></a>
<a href="mailto:{email}"><img src="https://img.shields.io/badge/Email-0d0d12?style=flat-square&logo=gmail&logoColor=8B7FB8&labelColor=1a1025"/></a>

<br/><br/>

<sub>«всё проходит. кроме репозиториев.»</sub>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1025,50:0d0d12,100:0d0d12&height=100&section=footer" width="100%"/>

</div>
