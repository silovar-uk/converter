# IMAGE FORGE

ブラウザ内だけで動く、16:9画像変換 + favicon一括生成ツールです。

## Vercelへの置き方

このフォルダの中身を、そのままGitHubリポジトリのルートへ置いてpushします。

- `index.html`：アプリ本体
- `app-icon.svg` / `app-icon-*.png` / `favicon.ico`：このアプリ自身のアイコン
- `app.webmanifest`：スマホで追加した場合などのアプリ情報

Vercelでは Framework Preset を **Other** にしてデプロイすればOKです。

## favicon生成機能

1. `FAVICON PACK GENERATOR` タブを開く
2. 元画像を1枚選ぶ
3. 名前・テーマカラー・トリミング方法を設定
4. ZIPをダウンロード
5. ZIP内の `favicon-head.html` を公開サイトの `<head>` に貼り付ける

画像・favicon生成はすべてブラウザ内で処理します。
