# 概要
* これはカスタマイズした js のファイル内容です。

# カスタマイズ js を読み込んでいるところ
* Snippets の footer-javascript.liquid に、下記を追記しました。
```
<!-- カスタマイズしたJavascriptの読み込み -->
{{ 'custom.js'  | asset_url | script_tag }}
```
