# 一蓮建設株式会社 ランディングページ

GitHub Pages でそのまま公開できる静的サイトです。

## 構成
- `index.html` … メインLP（トップページ）
- `recruit.html` … 採用情報ページ
- `exterior.html` … エクステリア事業部ページ
- `support.js` … ページ描画に必要なランタイム（削除しないでください）
- `web/` … 写真（Web最適化済み JPEG）
- `logo-mark.png` / `logo-full.png` … ロゴ

## GitHub Pages で公開する手順
1. GitHub で新しいリポジトリを作成します（例: `ichiren-lp`）。
2. このフォルダ内のファイルを **すべて** リポジトリにアップロードします（`index.html` がルート直下に来るように）。
3. リポジトリの **Settings → Pages** を開きます。
4. 「Build and deployment」の Source を **Deploy from a branch** にし、Branch を `main` / フォルダ `/ (root)` に設定して Save。
5. 数分後、`https://<ユーザー名>.github.io/<リポジトリ名>/` で公開されます。

## 画像の差し替え
写真は `web/` フォルダ内の JPEG を同名で置き換えると反映されます。
（例: `web/crew.jpg` を新しい集合写真に差し替え）

## メモ
- 日本語・英字フォントは Google Fonts から読み込むため、公開後もインターネット接続があれば正しく表示されます。
- 公式LINEのQRコードはトップページに画像を用意していません（LINEボタンからは友だち追加できます）。QR画像を表示したい場合はご相談ください。
- 採用ページの3職種カードは現在、応募メールが開くように設定しています。個別の求人詳細ページが必要な場合はご相談ください。
