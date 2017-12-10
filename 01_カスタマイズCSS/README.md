# 概要
* これはカスタマイズした css のファイル内容です。

# カスタマイズ css を読み込んでいるところ
* Layout の theme.liquid に、下記を追記しました。
```
<!-- カスタマイズしたCSSの読み込み -->
{{ 'custom.scss.css' | asset_url | stylesheet_tag }}
```
