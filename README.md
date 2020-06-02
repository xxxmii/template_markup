# template_markup
- マークアップで使うプロジェクトのテンプレート

## できること
`[]に囲まれてるものは、実行コマンド`
- css
    - [ `npm run compile:autoprefixer` ] ベンダープレフィックスを追加する
- sass
    - [ `npm run compile:scss` ] scssのコンパイル
    - [ `npm run watch:scss` ] scssをwatchして、コンパイル
    - minify（コンパイルされたcssは、自動でminifyされて出力される）
- js
    - [ `npm run watch:js` ] minify
- ブラウザ自動リロード
    - [ `npm run all` ] ファイルの更新をwatchして、自動でブラウザをリロードしてくれる。