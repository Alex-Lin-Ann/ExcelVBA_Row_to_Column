# 資料直向轉橫向
客人提供的發票千萬種，往往都會遇到需要將資料轉成橫向的窘境，才能鍵入公司的系統，不可能一個儲存格慢慢移動，所以開發了小小的工具，幫助同事解決問題

# 操作方式
![image](https://user-images.githubusercontent.com/37874182/204227026-85691d5e-dd8f-4533-8d23-ce2a59b15bb4.png)

1. 將直向資料貼在工作表[原始資料]A1欄。
2. 點擊下方的[刪除空白列]按鈕(此功能是刪除[原始資料]貼上後烈與列之間的空白，避免轉檔後因為空白而忽略將下一列資料轉入[結束]工作表當中)。
3. 點擊[Image]按鈕，即可完成轉檔。

# 參數設定與解說
* 儲存格B1 - 處裡[原始資料]的第幾欄，如: 1 代表指處裡第一欄(A)，2 代表處裡兩欄(A:B)，建議勿修改。
* 儲存格B2 - 處裡[原始資料]的列數(建議自動抓取 0)。
* 儲存格B11 - 參照[原始資料]的列數，若有空白列，將其整列刪除，如下圖: (發票種類較多，依經驗判斷並將結果轉至精準的列數。
- 刪除前(A欄多為空白)
- ![image](https://user-images.githubusercontent.com/37874182/204229360-1c3a4687-1f31-490d-90c4-b313d5f86e1c.png)
- 刪除後(參照A欄並整列空白刪除)
- ![image](https://user-images.githubusercontent.com/37874182/204229552-ea1c9414-967c-429b-82e0-a1a91872a197.png)

* 儲存格B3 - 處裡[結果]工作表被轉成列的儲存格數，如下圖:
- 設定
- ![image](https://user-images.githubusercontent.com/37874182/204227451-e1182b68-b25d-46b3-baf8-e36e8dbba23a.png)
- 原始資料
- ![image](https://user-images.githubusercontent.com/37874182/204226341-b6fa646f-93ff-40e6-8bbb-bc21de7c935d.png)
- 結果
- ![image](https://user-images.githubusercontent.com/37874182/204226459-909d9f37-1765-4ec8-aa0d-9d8f36af4e3c.png)

* 以下功能較少使用，點擊[刪除固定列數]按鈕
* 儲存格B9 - 一次移動N列，如 1 移動一列
* 儲存格B10 - 一次刪除N列，如 1 刪除一列

