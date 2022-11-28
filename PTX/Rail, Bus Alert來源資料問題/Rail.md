# Rail

[軌道通阻來源資料問題](https://iisicloud-my.sharepoint.com/:w:/g/personal/1010496_iisigroup_com/ESMmusM4WAxKhMZeBZBs-7UB2u1tq8LOZK9O4mNxkndXEQ?e=bdEFNg)
<!--
## Metro

### 臺北捷運

> https://api.metro.taipei/trtcmrtalertlistapi/motcptxapi/MRTAlertList

- 正常(Status=1)：`PublishTime`會一直更新，應該是"異常"=>"正常"當下的時間。
- 異常(Status!=1)：`PublishTime`會一直更新，應該是"異常"發生或更新狀態的時間。

### 高雄捷運

> https://service.krtc.com.tw/apiproject/api/mrtalertlist

- 正常(Status=1)：同"臺北捷運"。
- 異常(Status!=1)：`PublishTime`只給日期，應提供"異常"發生的時間。

### 桃園捷運

> https://www.tymetro.com.tw/PTX/AlertsList.xml

同"臺北捷運"。

### 高雄輕軌

> https://service.krtc.com.tw/apiproject/api/lrtalertlist

同"高雄捷運"。

## THSR

> https://www.thsrc.com.tw/APPool/OperationXML/GetAlertList.aspx

同"臺北捷運"。

## TRA

> SFTP ./res/TRAAlertList-\*.xml

- 正常(Status=1)：目前沒有資料可以參考，需要來源確認一下`PublishTime`的邏輯。
- 異常(Status!=1)：看起來沒問題。
-->
