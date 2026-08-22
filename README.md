# PDF Viewer - GitHub Pages : pdf-sandbox

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Version](https://img.shields.io/badge/version-0.1.0-green.svg)

概要

PDF-Viewer（ワークショップ用）のシンプルなリポジトリです。リポジトリ内の `docs/` に設置された簡易Web版PDFビューアーを使って、PDFファイルのプレビュー、ダウンロード、印刷が可能です。

オンライン版（GitHub Pages）:

- https://watanabe3tipapa.github.io/pdf-sandbox/

主な内容と機能（README に記載の事実のみ）

- docs/index.html に簡易なWEB版PDFビューアーを配置しています。
- ビューアーでPDFのプレビュー、ダウンロード、印刷が可能です。
- ブラウザ表示に不調があれば「リフレッシュ（再読み込み）」を行ってください。

開始・利用方法（事実として確認できる記述のみ）

ローカルで利用する場合

- ブラウザで `docs/index.html` を開いてご利用ください。

GitHub Pages で公開する場合

- 本リポジトリの `docs/` ディレクトリを GitHub Pages で公開するとオンラインで利用できます（README に明記の事実）。

PDF 配置について

- PDF ファイルは `docs/contents/` ディレクトリに格納してください（README に記載の通り）。
- 例: `docs/contents/sample1.pdf`, `docs/contents/sample2.pdf` など
- ファイル名や内容は自由です。サブディレクトリの作成も可能とされています。

リポジトリの構成（リポジトリルートに存在が確認できるファイル・ディレクトリ）

- .gitignore
- README.md
- docs/
- function/

（docs/index.html と docs/contents/ が利用されることが README から確認できます。`function/` の用途や中身は README からは明確ではありません。）

開発・保守状態

- デフォルトブランチ: main
- 最終更新（リポジトリ情報で確認）: 2025-12-20T02:31:29Z
- アーカイブ状態: アーカイブされていません（archived: false）

ライセンス

- MIT License（README に記載あり）

貢献

- プルリクエストやイシューの報告を歓迎します（README の記載に基づく）。

更新履歴

v0.1.0

- 初期リリース
- PDFビューアー
