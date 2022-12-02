

### Hello World 👋
I am a fullstack software engineer
- 🌱Learning how to solve front and back end problems
- 🌱Learning design patterns 
- 🌱Code Newbie

<br>


![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=sindiga-dev&show_icons=true&theme=radical)


[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=sindiga-dev&layout=compact)](https://github.com/anuraghazra/github-readme-stats)
<!--START_SECTION:waka-->
name: Waka Readme

on:
  schedule:
    # Runs at 12am IST
    - cron: '30 18 * * *'
  workflow_dispatch:
jobs:
  update-readme:
    name: Update Readme with Metrics
    runs-on: ubuntu-latest
    steps:
      - uses: anmol098/waka-readme-stats@master
        with:
          WAKATIME_API_KEY: ${{ secrets.waka_bd749556-e591-4b2d-a645-18babc0e7ea0 }}
          GH_TOKEN: ${{ secrets.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 }}
<!--END_SECTION:waka-->
