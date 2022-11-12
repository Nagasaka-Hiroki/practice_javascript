# practice_javascript
JavaScriptの学習。

## 主な参考URL
> - [MDN Web Docs](https://developer.mozilla.org/ja/)
> - [JavaScript Primer](https://jsprimer.net/)
> - [現代の JavaScript チュートリアル](https://ja.javascript.info/)

## チュートリアル
> - [http://jekyllrb-ja.github.io/docs/step-by-step/01-setup/](http://jekyllrb-ja.github.io/docs/step-by-step/01-setup/)  
まず上記URLのチュートリアルをやっていく。<br>
`jekyll new .`で土台を作ってからチュートリアルを開始する。<br>
（読み進めていくと`jekyll new .`で始めないほうが良さそうだがとりあえずそのまま進める)

## アクセス
以下のURLでアクセスできる。
> - [https://nagasaka-hiroki.github.io/practice_javascript/](https://nagasaka-hiroki.github.io/practice_javascript/)  

## 上手く表示されない
`index.html`は問題なく表示されたが、`about.html`や`staff.html`が上手く表示されない。  
→ `_config.yml`の`baseurl`と`url`を以下の値に設定した。
```
baseurl: "/practice_javascript"
url: "https://nagasaka-hiroki.github.io"
```
上手く行かない。アクセスするURLを変えると上手く表示できているのでURLの設定を誤っている。  
`_data/navigation.yml`を編集して設定してみる。  
→本質的な原因でなさそう。元に戻す。

`_config.yml`の`baseurl`と`url`を以下の値に設定した。
```
baseurl: ""
url: "https://nagasaka-hiroki.github.io/practice_javascript"
```
一応ローカル上では上手く行っている。