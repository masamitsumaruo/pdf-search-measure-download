# PDF検索＋測定 — ダウンロード

Windows デスクトップ用アプリ「**PDF検索＋測定**」の配布用リポジトリです（ダウンロード専用・ソースコードは含みません）。

## ダウンロード

👉 **ダウンロードページ: https://pdf-search-measure-dl.vercel.app**

または [Releases](../../releases/latest) から直接：

| ファイル | 用途 |
|---|---|
| `PDFSearchMeasure_Setup_zip.zip` | インストーラー版（推奨） |
| `PDFSearchMeasure_portable.zip` | インストール不要のポータブル版（`起動.bat` 同梱） |

## インストール手順（警告を出さないため）

1. ダウンロードしたZIPを右クリック →「プロパティ」→「**許可する**」にチェック → OK
2. ZIPを「**すべて展開**」
3. 展開したフォルダの `PDFSearchMeasure_Setup.exe`（ポータブル版は `起動.bat`）を実行

## 動作要件

- Windows 10 / 11（64bit）
- Microsoft Edge WebView2 ランタイム（Windows標準搭載。無い場合のみ [公式ページ](https://developer.microsoft.com/microsoft-edge/webview2/) から別途インストール）
- **Python 等は不要**（アプリに同梱済み）

## 主な機能

- 複数PDFの文字検索（一致70%以上・表記ゆれに強い）
- ヒット図面のベクター鮮明表示・拡大対応
- 図面上の距離測定（校正して実寸mm）

---
発行元: masamiz
