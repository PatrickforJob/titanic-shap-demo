# 🚢 鐵達尼號：AI 預測誰會活下來？

用鐵達尼號乘客資料訓練 AI 預測生還，並用 SHAP 分析 AI 的判斷依據。

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/PatrickforJob/titanic-shap-demo/blob/main/titanic_shap.ipynb)

## 使用方式

1. 點上方 **Open in Colab**
2. 上方選單 **執行階段 → 全部執行**（或 `Ctrl + F9`）
3. 往下捲動看結果

不需要安裝任何東西，也不需要會寫程式。

## 資料來源

`titanic.csv` 為 [OpenML Titanic (id 40945)](https://www.openml.org/d/40945) 的原始資料，未做任何修改（OpenML 標示授權：Public）。
原始整理者 Frank E. Harrell Jr. & Thomas Cason（Vanderbilt University），資料源自 Encyclopedia Titanica。僅供教學使用。

Notebook 會優先從本 repo 讀取 `titanic.csv`；若讀取失敗，會自動改用 `sklearn.datasets.fetch_openml` 從 OpenML 下載。
