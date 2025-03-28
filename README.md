## 📊 Total Donations Viewer

This simple HTML page fetches and displays the value from **cell A1** of a public Google Sheet and appends `LKR` to represent the donation amount. It uses the **Google Visualization API** to securely access and parse the sheet data in real-time.

### 💡 How it works:
- The Google Sheet is **published to the web**.
- The **Visualization API** fetches the sheet as a structured table.
- The script extracts the value of cell A1 (first row, first column).
- The donation amount is displayed in large green text with `LKR` appended.
- The heading shows: **Total Donations Received**.

> ⚠️ Make sure your Google Sheet is published to the web and the relevant data is in `Sheet1!A1`.

### License

MIT
