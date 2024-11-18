# Kaggle_Bike_Sharing_Demand

## ファイル構成

### 1. データフォルダ (`data/`)
- コンペティションで使用する元データ

### 2. 出力フォルダ (`out/`)
- モデルの予測結果（提出用CSVファイル）
- `submission-LGBM-final.csv`：LightGBMモデルによる予測結果
- `submission-RF-final.csv`：   RandomForestモデルによる予測結果

### 3. ソースコードフォルダ (`src/`)
- プロジェクトの主要なコードやノートブック
- `data_analysis_1.ipynb`：データ分析用コード
- `data_analysis_2.ipynb`：データ分析用コード
- `main.ipynb`：モデルの学習、ハイパーパラメータ調整、予測を実行するメインコード
- `model_comparison.ipynb`：時系列モデルおよび決定木モデルのなどの比較＆テスト