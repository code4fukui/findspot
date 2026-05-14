# findspot

公開されているSPARQLエンドポイントにクエリを実行し、日本の観光スポットを探索できるWebアプリケーションです。

## デモ

~~https://codeforfukui.github.io/findspot/~~ *(unavailable)*

デモでは、京都を中心としたインタラクティブなGoogleマップが表示され、観光スポットがマーカーで示されます。

![位置マーカーとナビゲーションボタンを備えた京都の地図を表示するfindspotのユーザーインターフェース](ss.jpg)

## 機能

- SPARQLクエリを使用して観光スポットのデータを取得・表示します。
- Googleマップ上にインタラクティブに位置を描画します。
- 現在地に最も近いスポットを検索します（ブラウザの位置情報許可が必要です）。
- Open Data Platform (ODP)や京都市など、複数のSPARQLエンドポイントをサポートしています。
- 京都、大阪、東京、福井など、日本のさまざまな都市へマップの中心をすばやく移動できるドロップダウンメニューを備えています。

## 要件

- JavaScriptが有効になっているモダンWebブラウザ。

## 使い方

1. ブラウザでデモページ *(demo unavailable)*を開きます。
2. 京都駅周辺の観光スポットとともにマップが読み込まれます。
3. ドロップダウンメニューを使用して、探索したい別の都市を選択します。
4. 「Nearest」ボタンをクリックすると、現在地に最も近いスポットを検索します。
5. 「Prev」および「Next」ボタンを使用して、表示されているスポットを切り替えます。

## データ / API

このプロジェクトは、以下のSPARQLエンドポイントからデータを取得しています：

- **Open Data Platform (ODP):** `https://sparql.odp.jig.jp/data/sparql`
- **京都市オープンデータ:** `https://sparql.city.kyoto.lg.jp/sparql/`

また、マップの描画にはGoogle Maps JavaScript APIを使用しています。

## ライセンス

このプロジェクトは [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/) の下でライセンスされています。
(c) Taisuke Fukuno
