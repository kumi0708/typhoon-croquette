# 台風コロッケ 風況ビューア

気象庁AMeDASの風況データをリアルタイム表示し、台風の軌跡・予報と近くのコロッケ購入スポットを確認できるWebアプリ。

## 機能

- **風況マップ** — 気象庁AMeDASの最新風向・風速を矢印で表示（10分更新）
- **台風情報** — 気象庁APIから台風の過去軌跡・予報進路・暴風域・予報円を表示
- **コロッケ購入スポット** — 現在地周辺のコンビニ・スーパー・精肉店をOpenStreetMapから検索

## 起動方法

```
start.bat をダブルクリック
```

Node.jsが必要です。起動後 `http://localhost:3000` が自動で開きます。

## データソース

- 風況データ: [気象庁 AMeDAS](https://www.jma.go.jp/bosai/amedas/)
- 台風データ: [気象庁 台風情報](https://www.jma.go.jp/bosai/typhoon/)
- 店舗データ: [OpenStreetMap](https://www.openstreetmap.org/) via Overpass API
- 地図タイル: [CARTO](https://carto.com/) / [Leaflet](https://leafletjs.com/)
