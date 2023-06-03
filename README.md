# IglKa
_________________________________________________________________________________________________________________________________________________________________________

## Learning full stack web-development with Django and other frameworks

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=IglKa&size_weight=0.5&count_weight=0.5)](https://github.com/anuraghazra/github-readme-stats)

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
          WAKATIME_API_KEY: ${{ secrets.WAKATIME_API_KEY }}
          GH_TOKEN: ${{ secrets.GH_TOKEN }}
<!--END_SECTION:waka-->
