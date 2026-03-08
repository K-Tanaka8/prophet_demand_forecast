# Prophetによる需要予測サンプル

このノートブックは、**Python + Prophet** を使って小売商品の需要予測を行うサンプルです。  
Google Colab でそのまま動作する、実務をイメージした簡易予測パイプラインを示しています。

## 特徴

- ダミーデータを生成して、SKUごとの販売数量を予測
- 祝日や月末、給料日などのカレンダー特徴量を追加
- Prophetモデルでの予測
- 予測精度評価（MAE、MAPE）
- 予測結果の可視化（平均値・上限・在庫目安）

## 実行環境

- Python 3.10+
- Google Colab 推奨
- ライブラリ: pandas, numpy, matplotlib, seaborn, prophet, joblib, holidays

## 実行方法

1. Google Colabで `prophet_demand_forecast_sample.ipynb` を開く  
2. 上から順にセルを実行する  
3. `demand_forecast_report.pdf` が生成される  

## 注意点

- 本ノートブックは**サンプル用途**のため、簡略化しています
- 実務で使用する場合は欠品処理、在庫ロジック、CV評価などを拡張してください
- このリポジトリのコードはポートフォリオ用です。閲覧は自由ですが、商用利用・再配布は不可です。

