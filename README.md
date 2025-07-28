# 中文筆順圖小工具

這是一個幫助海外孩子學習中文筆順的互動式網頁工具，輸入中文即可查找筆順，即使不會打中文字，也可以透過輸入英文單字找出中文詞語、筆順圖與注音。

This is an interactive web tool designed to help overseas children learn Chinese stroke order. By entering a Chinese character, users can look up its stroke order. Even if they can't type Chinese characters, they can still find Chinese words, stroke order diagrams, and Bopomofo (Zhuyin) pronunciation by entering English words.

---

## 🔍 功能特色 Features

- ✅ 主要用途：查找中文字筆順  
  - Primary purpose: Lookup Chinese character stroke order  
- ✅ 英文查中文詞語（內建詞庫 + 翻譯 API）  
  - Lookup Chinese words by entering English terms (via dictionary and translation API)  
- ✅ 顯示筆順靜態圖與動畫  
  - Show stroke order (static PNG + animated GIF)  
- ✅ 顯示注音符號（從萌典 API 取得）  
  - Display Bopomofo pronunciation via MoeDict API  
- ✅ 找不到字會跳出教育部字典連結  
  - Fallback to Taiwan’s Ministry of Education dictionary if no stroke found  
- ✅ PWA 支援，手機可加入主畫面  
  - PWA support, can be added to phone home screen  

---

## 🌐 線上體驗 Demo

GitHub Pages 網址：  
**https://ashleych34.github.io/hanzi-tools/**

Use Chrome or Safari for best experience. Mobile users can add it to Home Screen.

---

## 📁 專案結構 Project Structure

```
hanzi-tools/
├── index.html             # 主網頁 main page
├── manifest.json          # PWA 設定 PWA manifest
├── sw.js                  # 空的 service worker（可擴充）
├── icon-192.png           # PWA 小圖示 icon
├── icon-512.png           # PWA 大圖示 icon
├── edu_cedict.json        # 英文→中文 常見詞語對應詞庫
```

---

## 📚 資料來源 Data Sources

| 功能 Function     | 來源 Source |
|------------------|-------------|
| 筆順圖 Stroke Order | [twpen.com](https://www.twpen.com/) |
| 注音 Bopomofo     | [moedict.tw](https://www.moedict.tw/) |
| 翻譯翻譯 API Translation | [MyMemory](https://mymemory.translated.net/) |

---

## 🙋‍♀️ 作者 Author

Created by [Ashley](https://github.com/ashleych34)

這個專案是為了教育用途而製作。  
This project is designed for educational use. 
