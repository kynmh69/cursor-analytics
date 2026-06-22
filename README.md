# Cursor Team Usage Analytics

Cursor チームの利用状況CSVをブラウザ上で可視化するツールです。

## 公開URL

https://cursor-analytics.kynmh69.workers.dev

## 機能

- CSV アップロード（クリックまたはドラッグ&ドロップ）
- 日別コスト推移グラフ（ユーザー別）
- モデル別コスト内訳
- ユーザー別リクエスト数
- メンバー別詳細レポート

## 使い方

1. 上記URLにアクセス
2. Cursor ダッシュボードからエクスポートした `Team Usage` CSVをアップロード
3. グラフが自動生成される

## 技術スタック

- Vanilla HTML / CSS / JavaScript（単一ファイル）
- [Chart.js](https://www.chartjs.org/) — グラフ描画
- [PapaParse](https://www.papaparse.com/) — CSV パース
- Cloudflare Workers（静的サイトホスティング）

## デプロイ

```bash
npx wrangler deploy
```
