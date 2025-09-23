# Resume Repository

このリポジトリは職務経歴書を管理するためのものです。

## 職務経歴書の閲覧

職務経歴書の本体は [resume.md](./resume.md) にあります。

## PDF生成

以下のコマンドでPDFを生成できます：

```bash
npx markdown-pdf --css-path pdf-styles.css resume.md
```

このコマンドを実行すると、`resume.pdf` が生成されます。

## ファイル構成

- `resume.md` - 職務経歴書本体
- `pdf-styles.css` - PDF生成用のスタイルファイル
- `.markdown-pdf` - markdown-pdfの設定ファイル
