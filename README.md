# DISC 人格測驗

## 專案介紹
這是一個基於網頁的 DISC 人格測驗系統，使用純 HTML、CSS 和 JavaScript 打造。無需伺服器或資料庫，所有數據都儲存在瀏覽器的本地儲存中。

## 功能特點
- 簡潔直觀的用戶界面
- 20 個標準 DISC 測驗問題
- 分頁導航，每頁顯示 5 個問題
- 進度追蹤和自動儲存
- 詳細的測驗結果分析
- 雷達圖視覺化展示 DISC 分佈
- 報表列印和 PDF 下載功能
- 支援移動裝置和桌面瀏覽器

## 文件結構
```
DISC_test/
├── index.html              # 首頁：介紹和輸入姓名
├── quiz.html               # 測驗頁：展示問題和選項
├── results.html            # 結果頁：顯示測驗分析和報告
├── css/
│   ├── styles.css          # 通用和首頁樣式
│   └── quiz-styles.css     # 測驗和結果頁專用樣式
├── js/
│   ├── script.js           # 通用腳本功能
│   ├── quiz.js             # 測驗頁面功能
│   └── results.js          # 結果分析和顯示功能
├── DISC題目.txt             # 測驗問題參考資料
├── DISCovery Report.jpg    # 結果報告參考範例
└── README.md               # 項目說明文件
```

## 頁面說明

### 首頁 (index.html)
- 用戶輸入姓名，開始測驗
- 可以繼續之前未完成的測驗
- 提供 DISC 測驗的簡單介紹

### 測驗頁 (quiz.html)
- 每頁顯示 5 個問題
- 提供分頁導航和進度指示
- 自動儲存使用者回答
- 強制用戶回答當前頁面的所有問題才能繼續

### 結果頁 (results.html)
- 顯示 DISC 得分和百分比
- 提供外顯行為和內在動機分析
- 以雷達圖視覺化展示 DISC 分佈
- 分析個人特質、優勢、注意事項和職業建議
- 支援報告列印和 PDF 下載

## 用戶體驗改進

### 原始樣式
- 首頁使用原始樣式，保持熟悉和一致性

### 優化樣式 (quiz-styles.css)
- 測驗頁和結果頁使用優化樣式，但保持與首頁一致的色系和標題樣式
- 色彩系統統一使用首頁的配色方案：藍色系為主（#4a6fa5、#6b8cbc）
- 改進問題顯示，採用左對齊更直觀的閱讀體驗
- 選項改用白色背景，提高可讀性與內容重點
- 選項標籤統一為標準 A/B/C/D 格式，圓形藍底白字，提高識別度
- 指導語文字優化，更友好和專業
- 調整所有元素的間距，改善整體排版
- 優化導航和按鈕設計
- 結果頁面佈局和資訊呈現更加清晰

## 使用方法
1. 在首頁輸入您的姓名
2. 點擊「開始測驗」按鈕
3. 回答所有的測驗問題，每個問題選擇最符合您的描述
4. 完成所有問題後，查看您的詳細 DISC 分析報告
5. 可以下載或列印報告留存

## 瀏覽器支援
- Chrome
- Firefox
- Safari
- Edge
- Opera

## 資料安全
所有測驗數據僅儲存在您的本地瀏覽器中，不會上傳到任何伺服器。如果清除瀏覽器數據，您的測驗記錄將被刪除。

## 授權

# 上傳到Git的必要資訊


# 初始化本地Git倉庫
git init

# 添加所有文件到暫存區
git add .

# 創建首次提交
git commit -m "初始提交 - DISC測驗完整功能"

# 添加遠端倉庫（將URL替換為您的倉庫URL）
git remote add origin 您的倉庫URL

# 推送到遠端倉庫的主分支
git push -u origin main
```

如果您已經有初始化的Git倉庫，只需執行：

```bash
# 檢查Git狀態
git status

# 添加所有文件到暫存區
git add .

# 提交更改
git commit -m "03.微調"

# 推送到遠端倉庫
git push
