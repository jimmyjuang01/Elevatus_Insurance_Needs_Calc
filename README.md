# Elevatus 保障需求分析系統 (v7.6)
> **Cross-Border Financial Consulting Tool**

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Chart.js](https://img.shields.io/badge/chart.js-F5788D.svg?style=for-the-badge&logo=chart.js&logoColor=white)

本系統是一套專為理財顧問設計的專業保障缺口分析工具，旨在協助顧問透過視覺化圖表與精確演算，引導客戶規劃身故、重大疾病與長期照護的財務儲備。

## 🔗 線上展示 (Live Demo)
[點此開啟分析系統](https://jimmyjuang01.github.io/Elevatus_Insurance_Needs_Calc/)

---

## ✨ 核心特色

### 1. 專業視覺化互動
* **雙環圖分析**：內環顯示「現有資產」，外環顯示「保障缺口」，並支援移動滑鼠顯示細節明細。
* **動態數字動畫**：變更左側數據時，總缺口金額會即時跳動滾動，增強客戶互動感。
* **智慧介面 (Placeholder)**：預設顯示淺灰色提示字，保持畫面簡潔，點擊即可輸入。

### 2. 多國語系與在地化精算
* **中英雙語切換**：支援即時語系變更，包含所有下拉選單與圖表說明。
* **長照路徑切換**：內建 **美國 (US)** 三級照護預設值與 **台灣 (TW)** 月費自定義模式。
* **通膨精算 (FV)**：支援自定義通膨率，將未來需求換算為未來值，並在 PDF 報告中清晰標註。

### 3. 自動化與匯出功能
* **Google Sheet 串接**：一鍵「儲存諮詢紀錄」，自動將客戶資料（含 Email、子女明細）上傳至雲端資料庫。
* **專業 PDF 產出**：優化列印排版，確保子女資料單行排列，顏色對比鮮明，適合正式提案。
* **一鍵清空模式**：提供快速重置按鈕，清空所有輸入與預設提示字，方便重新操作。

---

## 🛠 操作手冊

### 步驟 A：基本資料設定 (Section 00)
1. 選取負責**顧問**名單。
2. 輸入客戶姓名、性別、電話與 **E-mail**。
3. 設定**子女數量**，系統將動態生成姓名、性別與年齡欄位。

### 步驟 B：需求評估 (Section 01 - 03)
1. **家庭責任**：填寫房貸、債務、年收入替代年限。
2. **醫療福利**：設定重疾應急金與醫療自付上限。
3. **長照準備**：選擇地區（US/TW），選取照護等級或填寫月費估算。

### 步驟 C：現有資產與產出
1. **現有資產**：輸入目前保額與流動資金。
2. **缺口總覽**：觀察雙環圖分佈，若有需求可開啟「通膨精算 (FV)」。
3. **儲存與列印**：點擊「儲存」備份資料，或「列印 PDF」直接交付予客戶。

---

## 📅 版本紀錄 (Changelog)
* **v7.6 (2026-04-06)**: 修復清空按鈕邏輯（徹底清空提示字）、補回 Email 欄位、強化 PDF 通膨率文字對比。
* **v7.2**: 加入總額跳動動畫與圖表渲染防呆機制。
* **v6.8**: 修正 PDF 子女資料跑版與下拉選單翻譯同步問題。

---

## 👥 預設顧問名單
* Jimmy Chuang
* Wendy Yun
* Steve Yun
* Pablo Lin

---
© 2026 Elevatus Business Consultants. 本系統僅供財務規劃初步參考。
