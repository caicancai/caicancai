Hola Amigo 🤣
I'm HangC, a software engineer who occasionally ponders some odd questions.

[![GitHub](https://img.shields.io/badge/dynamic/json?logo=github&label=GitHub&labelColor=495867&color=495867&query=%24.data.totalSubs&url=https%3A%2F%2Fapi.spencerwoo.com%2Fsubstats%2F%3Fsource%3Dgithub%26queryKey%3Dhayschan&style=flat-square)](https://github.com/caicancai)

Here are some ideas to get you started:
- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

[![我的 GitHub 数据](https://github-readme-stats.vercel.app/api?username=caicancai)]()
name: WakaTime Readme

on:
  push:
    branches:
      - master
  schedule:
    - cron: '0 19 * * *'

jobs:
  update-readme:
    runs-on: ubuntu-latest
    steps:
      - uses: athul/waka-readme@master
        with:
          WAKATIME_API_KEY: ${{ secrets.WAKATIME_API_KEY }}

