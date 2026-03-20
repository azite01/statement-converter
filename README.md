# Bank or Credit Card Statement to CSV Converter

[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen.svg)](https://paskonline.github.io/statement-converter/)

A lightweight, purely client-side web tool designed to quickly convert bank or credit card statement PDFs into clean, formatted CSV files. 

This tool eliminates the need for manual data entry, making it perfect for rapid month-end financial reconciliation and expense tracking. It cleans up the messy, unformatted text that happens when copying directly from a PDF and automatically organizes it into structured columns.

## 🔒 Privacy & Security

**Your financial data never leaves your device.** 

Most bank statements are provided as password-protected PDFs, which prevents direct export to Excel. To get around this, many users resort to third-party online "PDF Unlockers" or "PDF to CSV" converters, unknowingly uploading their sensitive financial data to external servers. 

This tool solves that security risk. It is built entirely with vanilla HTML, CSS, and JavaScript with no backend or database. 

By simply opening your password-protected PDF on your own computer, copying the text, and pasting it here, all parsing and math are executed locally within your web browser's memory. No files are uploaded, and once you close the tab, the data vanishes.

## ✨ Features

* **Smart Parsing:** Automatically detects dates and transaction amounts, ignoring headers, footers, and messy PDF line breaks.
* **Auto-Calculated Balances:** Detects the "Opening Balance" and maintains a running calculation of your balance across all Debits and Credits.
* **Dr / Cr Separation:** Splits transactions into dedicated Debit and Credit columns for easy spreadsheet formulas.
* **Mobile Responsive:** Fully optimized for mobile devices with a swipeable data table and touch-friendly interface.
* **Instant Export:** Generates a ready-to-use `.csv` file with a single click.

## 🚀 How to Use

1. Go to the [Live Tool](https://paskonline.github.io/statement-converter/).
2. Open your Bank Statement PDF.
3. Select all the text in the PDF (`Ctrl + A` or `Cmd + A`) and copy it.
4. Paste the text into the input box on the website.
5. Verify the parsed transactions in the preview table.
6. Click **Download CSV** to save the formatted file to your device.

## 🛠️ Built With

* HTML5
* CSS3
* Vanilla JavaScript (ES6)

---
*Note: This is an independent tool and is not officially affiliated with or endorsed by an authorized bank.*
