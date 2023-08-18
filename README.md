### Hi there  Guilherme Augusto👋
 

 name: gitartwork from a contribution graph
 on: 
   push:
   schedule:
     - cron: '* */24 * * *'
 jobs:
   build:
     name: Make gitartwork SVG
     runs-on: ubuntu-latest
     steps:
       - uses: actions/checkout@v3
       - uses: jasineri/gitartwork@v1
         with:
            # Use this username's contribution graph  
            user_name: jasineri
            # Text on contribution graph 
            text: JASINERI
       - uses: jasineri/simple-push-action@v1



![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&bg_color=00000000)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=github-readme-stats)](https://github.com/anuraghazra/github-readme-stats)
