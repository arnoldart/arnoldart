### Hi there 👋

Hi my name is arnold, i'm 16 years old and i'm still a beginner for the js and php programming languages

![arnoldart's github stats](https://github-readme-stats.vercel.app/api?username=arnoldart&show_icons=true)

name: arnoldart

on:
  workflow_dispatch:
  schedule:
    # Runs at 12am UTC
    - cron: "0 0 * * *"

jobs:
  update-readme:
    name: Update this repo's README
    runs-on: ubuntu-latest
    steps:
      - uses: athul/waka-readme@master
        with:
          WAKATIME_API_KEY: ${{ secrets.07e8201d-3c21-4d31-9c4b-73863feed444 }}
          GH_TOKEN: ${{ secrets.0ca7413df48ce1b1871763417041a84be2a77791 }}
          REPOSITORY: <arnoldart/arnoldart>
