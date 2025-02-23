[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)


## Wiegand (Reverse) 重構工具
如果您沒有 ESP8266 開發板，但想從 `Wiegand (Reverse)` 推導出 `Wiegand (Reverse shifted 16, reconstructed)`，可以使用以下方法：

* **線上工具：** 使用 [線上 Wiegand 推導工具](https://stjl.github.io/UID-Reverse-to-Wiegand-shifted-16-Decoder-website/)。

如果您有 ESP8266 開發板，並想了解如何在 ESP8266 上配合 RFID-RC522 實現 Wiegand Reverse 功能，請查看我的另一個專案：

* **ESP8266 專案：** [ESP8266-RFID-Wiegand-Reverse-shifted-16-Decoder](https://github.com/stJL/ESP8266-RFID-Wiegand-Reverse-shifted-16-Decoder)


輸入 `Wiegand (Reverse)` 的十進制值，即可得到推導結果。

## 簡介

這個網站提供一個 Wiegand 重構工具，用於將反向 Wiegand 碼轉換為原始 Wiegand 碼。
* *(提示：本程式碼的位移方法可能與某些 Soyal 系列門禁系統相符，但需進行實際測試驗證。)*

## 功能

* **Wiegand 碼重構：**
    * 使用者可以在輸入框中輸入反向 Wiegand 碼，然後點擊「推導」按鈕，網站會自動將其轉換為原始 Wiegand 碼。
* **儲存結果：**
    * 每次成功轉換後，結果會自動儲存到瀏覽器的 `localStorage` 中。
* **顯示儲存結果：**
    * 網站會顯示所有儲存的結果，方便使用者查看和管理。
* **複製所有儲存結果：**
    * 使用者可以點擊“複製所有結果”按鈕，將所有儲存的結果複製到剪貼簿。
* **錯誤處理：**
    * 如果使用者輸入無效的 UID 碼，網站會顯示錯誤訊息。

## 使用方法

1.  **輸入 UID 碼：**
    * 在輸入框中輸入您要轉換的反向 Wiegand 碼。
2.  **執行重構：**
    * 點擊「推導」按鈕，網站會自動執行轉換。
3.  **查看結果：**
    * 轉換後的 Wiegand 碼會顯示在結果區域。
4.  **查看儲存結果：**
    * 所有儲存的結果會顯示在「儲存的結果」區域。
5.  **複製所有儲存結果：**
    * 點擊“複製所有結果”按鈕，將所有儲存的結果複製到剪貼簿。

## 技術棧

* HTML
* CSS
* JavaScript

## 儲存

* 轉換結果儲存在瀏覽器的 `localStorage` 中。

## 注意事項

* 請確保輸入有效的 UID 碼。
* 當使用“複製所有結果”時，結果會使用換行符號分段。

**重要提示：**
* 本專案僅為調查工具，實際 Wiegand 編碼可能更複雜。
* 為了獲得準確的 Wiegand 碼，您需要訪問控制系統的規格。
* 本專案不包含奇偶校驗位計算。

### 貢獻 (Contributions)

歡迎任何形式的貢獻！如果您有任何改進建議或發現任何錯誤，請隨時提交 Pull Request 或 Issues。

### 授權 (License)

本專案使用 MIT 授權。詳細資訊請參閱 `LICENSE` 檔案。


# Wiegand (Reverse) Reconstructor

If you don't have an ESP8266 development board but want to derive `Wiegand (Reverse shifted 16, reconstructed)` from `Wiegand (Reverse)`, you can use the following method:

* **Online Tool:** Use the [Online Wiegand Reconstructor](https://stjl.github.io/UID-Reverse-to-Wiegand-shifted-16-Decoder-website/).

If you have an ESP8266 development board and want to learn how to implement Wiegand Reverse functionality with RFID-RC522 on ESP8266, please check out my other project:

* **ESP8266 Project:** [ESP8266-RFID-Wiegand-Reverse-shifted-16-Decoder](https://github.com/stJL/ESP8266-RFID-Wiegand-Reverse-shifted-16-Decoder)


Enter the decimal value of `Wiegand (Reverse)` to get the derived result.
* *(Hint: The shift method in this code may be compatible with some Soyal series access control systems, but actual testing and verification are required.)*

## Introduction

This website provides a Wiegand reconstructor tool to convert reverse Wiegand codes to original Wiegand codes.

## Features

* **Wiegand Code Reconstruction:**
    * Users can enter the reverse Wiegand code in the input field and click the "Reconstruct" button to automatically convert it to the original Wiegand code.
* **Save Results:**
    * Each successful conversion result is automatically saved in the browser's `localStorage`.
* **Display Saved Results:**
    * The website displays all saved results for users to view and manage.
* **Copy All Saved Results:**
    * Users can click the "Copy All Results" button to copy all saved results to the clipboard.
* **Error Handling:**
    * If the user enters an invalid UID code, the website displays an error message.

## Usage

1.  **Enter UID Code:**
    * Enter the reverse Wiegand code you want to convert in the input field.
2.  **Perform Reconstruction:**
    * Click the "Reconstruct" button to automatically perform the conversion.
3.  **View Results:**
    * The converted Wiegand code is displayed in the result area.
4.  **View Saved Results:**
    * All saved results are displayed in the "Saved Results" area.
5.  **Copy All Saved Results:**
    * Click the "Copy All Results" button to copy all saved results to the clipboard.

## Technology Stack

* HTML
* CSS
* JavaScript

## Storage

* Conversion results are stored in the browser's `localStorage`.

## Notes

* Please ensure that you enter a valid UID code.
* When using "Copy All Results," the results will be separated by line breaks.

**Important Notes:**
* This project is only an investigative tool, and real Wiegand encoding may be more complex.
* To get accurate Wiegand codes, you need the specifications of your access control system.
* This project does not include parity bit calculations.

### Contributions

Contributions of any kind are welcome! If you have any suggestions for improvement or find any bugs, please feel free to submit a Pull Request or Issues.

### License

This project is licensed under the MIT License. See the `LICENSE` file for details.




