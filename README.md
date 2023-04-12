# Fast AIT Corrector

## 説明

このプログラムは、HTMLソースコード中のaタグのtitle属性をimgタグのtitle属性にコピーし、aタグを削除するという処理を行います。この処理は、SEO対策やアクセシビリティ向上のために有用です。このプログラムは、JavaScriptで実装されており、ブラウザ上で動作します。

## インストール

このプログラムには特別なインストール方法はありません。ソースコードをダウンロードまたはクローンして、任意のエディタで開いてください。

## 実行方法

1. index.htmlファイルをブラウザで開きます。
2. textarea要素に変換したいHTMLソースコードを入力します。
3. alt属性のコピー方法をラジオボタンで選択します。
4. 修正するボタンをクリックします。
5. 下部のtextarea要素に修正されたHTMLソースコードが表示されます。

## 使用技術

- HTML
- CSS
- JavaScript

## ライセンス

このプログラムはMITライセンスのもとで公開されています。詳細は[LICENSE](LICENSE)ファイルを参照してください。

## 貢献者

このプログラムは以下の方々によって開発されました。

- [Rene](https://github.com/rene4784)
- [ChatGPT Mar 23 Version](https://chat.openai.com/chat)
- [Bing AI Chat](https://www.bing.com/search?q=Bing+AI&showconv=1&FORM=hpcodx)

このプログラムにはJestを用いた単体テストが用意されています。テストを実行するには以下のコマンドを実行してください。

```bash
npm install
npm test
```

## コード規約

このプログラムではESLintとPrettierを用いてコード規約を統一しています。コード規約に従ってフォーマットするには以下のコマンドを実行してください。
```bash
npm install
npm run format
```
