# Splatoon2の動画圧縮を楽にしたかった話

2017-11-06の社内勉強会での発表資料です。

[reveal.js](https://github.com/hakimel/reveal.js/)使ってます。

スライド生成コマンド

```
pandoc -f markdown -t revealjs --template=default.revealjs --self-contained --slide-level=2 --css=custom.css -o index.html index.md
```
