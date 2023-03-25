# html-to-md

`html-to-md`はHTMLファイルをMarkdownファイルに変換するためのコマンドラインツールです。HTMLドキュメントをMarkdownに変換することで、プレーンテキストエディタを使用して書式付きテキストを作成するための軽量マークアップ言語を利用できます。

## 使い方

`html-to-md`は2つの必須引数が必要です:

- `-f`または`--htmlFile`: Markdownに変換したいHTMLファイルのパス。
- `-o`または`--outputDir`: 生成されたMarkdownファイルを保存するディレクトリのパス。

また、2つのオプション引数を使用することもできます:
- `-l`または`--local`: HTMLファイルがローカルにある場合、このフラグをtrueに設定します。
- `-h`または`--help`: ヘルプメッセージを表示して終了します。

`html-to-md`の使用例を示します:

```
html-to-md -f /path/to/file.html -o /path/to/output/directory/
```