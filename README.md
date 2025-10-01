# Resume Repository

このリポジトリは職務経歴書を管理するためのものです。

## 職務経歴書の閲覧

職務経歴書の本体は [resume.md](./resume.md) にあります。

## PDF生成

### Mac環境

```bash
npx markdown-pdf --css-path pdf-styles.css resume.md
```

### Ubuntu/WSL2環境

事前に依存パッケージをインストール：

```bash
sudo apt-get update
sudo apt-get install -y fonts-noto-cjk libnss3 libnspr4 libatk1.0-0 libatk-bridge2.0-0 libcups2 libdrm2 libxkbcommon0 libxcomposite1 libxdamage1 libxfixes3 libxrandr2 libgbm1 libasound2
```

PDF生成：

```bash
npx md-to-pdf resume.md --config-file .md-to-pdf.json --document-title "職務経歴書"
```

いずれのコマンドを実行しても、`resume.pdf` が生成されます。

## ファイル構成

- `resume.md` - 職務経歴書本体
- `pdf-styles.css` - PDF生成用のスタイルファイル
- `.markdown-pdf` - markdown-pdfの設定ファイル
