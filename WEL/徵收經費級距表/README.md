# 徵收經費級距表

- [issue 35-少開一支有關徵收經費級距表的API](https://gitlab.transportdata.tw/wel/welfare/welfare-admin-api/-/issues/35)
- [(ok)04_附錄四 資料庫規格書_v14](https://iisicloud.sharepoint.com/:w:/r/sites/111850/_layouts/15/Doc.aspx?sourcedoc=%7B0AC4AB0D-C780-4BDA-899E-8FDD60249AD4%7D&file=(ok)04_%E9%99%84%E9%8C%84%E5%9B%9B%20%E8%B3%87%E6%96%99%E5%BA%AB%E8%A6%8F%E6%A0%BC%E6%9B%B8_v14.docx&action=default&mobileredirect=true)
  
## 資料表欄位對應

| UI Field Name               | COLLECT_PERFORMANCE | ColPerformance |
| --------------------------- | ------------------- | -------------- |
| 年附徵                      | PRICE1              | AnnualAmount   |
| 水費減收-經費               | PRICE2              | Abatement      |
| 徵收支出-水事業手續費       | PRICE4              | HandlingFee?   |
| 徵收支出-經濟部行政費       | PRICE5              | CentreFee?     |
| 移列下年度-水費減收經費     | PRICE6              | NextAbatement  |
| 預估經費淨額                | PRICE7              | SubTotal?      |
| 撥至縣市政府經費-縣市行政費 | PRICE8              | ChiefdomFee?   |
| 撥至縣市政府經費-各鄉鎮淨額 | PRICE9              | TownFeedback?  |
| 水費減收比例                | PRICE3 * 100        | AbatementRate * 100  |
