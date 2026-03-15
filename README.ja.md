# findspot

観光地を探す（京都、ODPのSPARQLエンドポイントを利用）

## デモ
https://codeforfukui.github.io/findspot/

## 機能
- SPARQLクエリを使って観光地を検索
- Google Mapsインターフェイスで結果を表示
- 複数のSPARQLエンドポイント（ODP、京都市）に対応
- ユーザーの現在地から最も近い観光地を探す機能

## 必要環境
- 最新のウェブブラウザ

## 使い方
1. [デモページ](https://codeforfukui.github.io/findspot/)をウェブブラウザで開きます。
2. 地図に京都周辺の観光地が表示されます。
3. 「最短」ボタンをクリックすると、現在地から最も近い観光地がフォーカスされます（位置情報の許可が必要）。
4. 「前へ」「次へ」ボタンで観光地を移動できます。

## データ・API
このプロジェクトではオープンデータポータル(ODP)と京都市のSPARQLエンドポイントを利用して観光地情報を取得しています。

## ライセンス
このプロジェクトは [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/) ライセンスの下で公開されています。