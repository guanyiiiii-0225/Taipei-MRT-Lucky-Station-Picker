# 🚇 Taipei MRT Lucky Station Picker (台北捷運幸運拉霸機)

一個可愛的 Web 應用程式，透過 3D 拉霸機的介面，隨機為你選出台北捷運的站點。

> **A cute, interactive web application that randomly selects a destination from the Taipei Metro network using a 3D slot machine interface.**

## ✨ 特色 (Features)

*   **擬真 3D 拉桿動畫**：使用純 CSS 3D Transform 技術製作，包含圓潤的握把與流暢的機械動態。
*   **捷運主題配色**：完整收錄台北捷運各路線（文湖線、紅線、綠線...等），並依照官方色系進行粉嫩風（Pastel）的視覺優化。
*   **戰利品展示區**：主畫面僅顯示已抽中的車站，隨著抽獎次數增加，你的「捷運站收藏」會越來越豐富。
*   **高度客製化設定**：
    *   可透過設定面板 (Settings) 自由勾選/取消想要參與抽獎的車站。
    *   支援「全選/取消全選」功能，方便一次管理整條路線。
*   **智慧排序**：車站列表與戰利品皆依照「路線顏色」與「車站編號」自動排序，整齊美觀。
*   **RWD 響應式設計**：無論在電腦或手機上都能完美體驗。
*   **慶祝特效**：抽中站點時會有精彩的彩帶 (Confetti) 噴發效果。

## 🛠️ 技術棧 (Tech Stack)

*   **HTML5**: 語意化標籤結構。
*   **CSS3**: 
    *   利用 `transform-style: preserve-3d` 建構 3D 拉桿模型。
    *   使用 `radial-gradient` 繪製擬真球體光影。
    *   CSS Animations 處理互動回饋。
*   **JavaScript (Vanilla JS)**: 
    *   處理抽獎邏輯、資料排序、DOM 操作與設定管理。
*   **Library**: [canvas-confetti](https://github.com/catdad/canvas-confetti) (用於慶祝特效)。

## 🚀 如何使用 (How to Use)

1.  下載專案中的 `index.html` 檔案。
2.  直接使用瀏覽器（Chrome, Edge, Safari 等）打開該檔案即可開始使用。
3.  點擊 **"Station Settings"** 可以展開設定列表，篩選你想去的路線。
4.  按下 **"SPIN"** 或點擊 **3D 拉桿** 開始抽獎！

## 🤝 致謝 (Credits)

本專案與 **Google AI Studio** 共同協作完成(包含README.md)。

---

# 🚇 Taipei MRT Lucky Station Picker

Looking for a random adventure in Taipei? This interactive web application features a cute, pastel-styled 3D slot machine that helps you randomly select a destination from the Taipei Metro network.

## ✨ Features

*   **Realistic 3D Lever**: Built with pure CSS 3D transforms, featuring a rounded handle and smooth animations.
*   **Taipei MRT Branding**: Includes all major MRT lines with customized pastel colors for better readability.
*   **Collection View**: The main screen displays only the stations you've picked, creating a colorful collection of destinations.
*   **Customizable Settings**: 
    *   Filter specific stations or lines via the settings panel.
    *   "Select All / Unselect All" buttons for quick line management.
*   **Smart Sorting**: Stations are automatically sorted by Line and Station ID.
*   **Responsive Design**: Works perfectly on both desktop and mobile devices.
*   **Celebration Effects**: Confetti pops when a station is selected!

## 🛠️ Tech Stack

*   **HTML5 & CSS3**: Advanced 3D transforms and animations.
*   **JavaScript**: Core logic for the randomizer and DOM manipulation.
*   **canvas-confetti**: For the celebration effects.

## 🚀 Getting Started

1.  Download the `index.html` file.
2.  Open it in any modern web browser.
3.  Click **"Station Settings"** to filter your options.
4.  Click **"SPIN"** to start your journey!

## 🤝 Credits

This project was co-created with **Google AI Studio**(including README.md).
