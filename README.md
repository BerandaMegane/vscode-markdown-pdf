# VSCode Markdown PDF

Visual Studio Code の Markdown ファイルを、GitHub 風のスタイルで HTML または PDF に出力するための設定です。

VSCode + Markdown PDF 拡張機能を用いた Markdown による資料の作成環境を構築できます。

## 内容

`.vscode/settings.json` および `css/github-markdown.css` は、資料作成する際に使用する設定ファイルです。

- `.vscode/settings.json`: Markdown PDF 拡張機能の出力設定。PDF は `output` ディレクトリに保存されます。
- `css/github-markdown.css`: HTML/PDF に適用するスタイルシート。上流の CSS を一部変更しています。
- `css/LICENSE`: スタイルシートの上流プロジェクトに付属する MIT License。

## 使い方

1. Visual Studio Code に [Markdown PDF 拡張機能](https://marketplace.visualstudio.com/items?itemName=yzane.markdown-pdf) をインストールします。
2. Chromium のインストールが完了するまで待ちます。必要に応じて VS Code を再起動してください。
3. 出力する Markdown ファイルを開き、コマンドパレットから `Markdown PDF: Export (pdf)` または `Markdown PDF: Export (html)` を実行します。
4. 出力ファイルは `output` ディレクトリに保存されます。

PDF の余白、縮尺、フッターなどは `.vscode/settings.json` で変更できます。詳しくは [Markdown PDF 拡張機能のドキュメント](https://marketplace.visualstudio.com/items?itemName=yzane.markdown-pdf) を参照してください。

## CSS のライセンスと出典

`css/github-markdown.css` は [sindresorhus/github-markdown-css](https://github.com/sindresorhus/github-markdown-css) を基に、一部を変更したものです。CSS の再配布には上流プロジェクトの MIT License が適用され、その原文を [`css/LICENSE`](css/LICENSE) に同梱しています。

## ライセンス

このリポジトリの内容は、別途記載があるものを除き MIT License で公開します。ライセンスの詳細は [`LICENSE`](LICENSE) を参照してください。`css/github-markdown.css` には上流プロジェクトの著作権表示とライセンスも適用されます。

## 参考資料

- [Markdown から PDF を生成する環境構築手順（VSCode＋Markdown PDF）](https://qiita.com/crlf/items/bb1bc49ede095746c19c)
