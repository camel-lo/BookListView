# 圖書管理程式
## 專案簡介
本專案為一個使用 C# Windows Forms 開發的圖書管理模擬程式。主要展示如何操作 `ListView` 清單檢視控制項，並搭配 `ImageList` 影像清單來實作有圖片與文字搭配的書籍展示介面。

程式內建多本古典文學書籍資料（包含書名、作者、類別）。使用者可以透過下拉式選單動態切換不同的檢視模式，並能透過雙擊書籍項目來模擬借書流程，將書籍加入借閱清單中。

## 執行說明
1. **瀏覽書籍與切換檢視**：
   * 程式啟動後，左側主畫面預設會以「大圖示」模式顯示圖書清單。
   * 點選右上方「檢視方式」的下拉式選單，可自由切換五種檢視模式：大圖示、詳細資料、小圖示、清單、大圖示加詳細資料。
2. **借閱操作**：
   * 在欲借閱的書籍項目上 **連續點擊兩下**，系統會跳出訊息方塊詢問「確定要借閱嗎？」，點選「是」後，系統會檢查該書籍是否已在右下角的「借書清單」中，若無則將其加入。

## 程式截圖
<img width="837" height="568" alt="image" src="https://github.com/user-attachments/assets/db5b80a5-7673-4fc3-9653-b7589fda3602" />
<br>
<img width="835" height="568" alt="image" src="https://github.com/user-attachments/assets/2e4e13a3-fc1d-4967-846d-ae81aa4ec73c" />
<br>
<img width="834" height="569" alt="image" src="https://github.com/user-attachments/assets/31e50817-38ca-4d24-8cde-a0be6eceffb5" />
