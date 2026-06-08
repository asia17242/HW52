# 🧠 十大機器學習方法：互動式視覺化資訊圖表

這是一個基於 HTML5 Canvas、Tailwind CSS 與 Streamlit 建立的**機器學習演算法動態視覺化教學教材**。使用者可以透過直觀的調整參數，觀察演算法的動態收斂行為。

## 🚀 線上展示 (Live Demo)

👉 [點此觀看 Streamlit 線上展示](https://asia17242-hw52.streamlit.app) *(請將此連結替換為您在 Streamlit 部署後的實際網址)*

---

## 🎨 專案特色

* **精心設計的淺黃色/奶油色主題**：符合現代高質感 UI 設計，具備舒適的閱讀對比度與玻璃感字卡設計。
* **10 大核心演算法教學**：
  1. 線性回歸 (Linear Regression)
  2. 邏輯回歸 (Logistic Regression)
  3. 決策樹 (Decision Tree)
  4. 隨機森林 (Random Forest)
  5. 梯度提升樹 (GBDT)
  6. 支持向量機 (SVM)
  7. K-近鄰演算法 (K-NN)
  8. K-平均分群 (K-Means)
  9. 主成分分析 (PCA)
  10. 人工神經網路 (ANN)
* **動態視覺化實驗室**：包含 10 組即時互動 Canvas 實驗，支援新增數據點、拖動滑桿觀察擬合曲線、發射神經網絡前向傳播動畫等。

---

## 💻 本地端運行步驟

### 1. 安裝相依套件
請確認您的電腦已安裝 Python，並執行以下指令安裝 Streamlit：
```bash
pip install -r requirements.txt
```

### 2. 啟動應用程式
在專案根目錄下執行：
```bash
streamlit run streamlit_app.py
```
執行後，系統會自動在瀏覽器中開啟 `http://localhost:8501` 本地測試網頁。

---

## 📂 專案結構

```text
├── code_artifact.html    # 主要的互動式前端網頁 (HTML/JS/Canvas)
├── streamlit_app.py      # Streamlit Python 後端服務 (嵌入 HTML)
├── requirements.txt      # 專案相依性清單
└── README.md             # 專案說明文件
```