# Bus

[公車通阻來源資料問題](https://iisicloud-my.sharepoint.com/:w:/g/personal/1010496_iisigroup_com/EWofQA4SUN1EjZLPR80gGYYBz_PtrOGwfkKwFdCx6cfr7Q?e=dzUfK1)

<!--
## 公總公車

> https://web.taiwanbus.tw/eBUS/subsystem/WebService/busalertlist.ashx?City={0}

- 正常(Status=1)：`PublishTime`未提供，應提供"異常"=>"正常"當下的時間。
- 異常(Status!=1)：看起來沒問題。

## 臺北公車

> https://tcgbusfs.blob.core.windows.net/blobbus/GetBusAlertList.gz

- 正常(Status=1)：目前沒有資料可以參考，需要來源確認一下`PublishTime`的邏輯。
- 異常(Status!=1)：看起來沒問題。

## 高雄公車

> https://ibus.tbkc.gov.tw/xmlptx/routes/alerts

- 正常(Status=1)：目前沒有資料可以參考，需要來源確認一下`Alert.UpdateTime`的邏輯。
- 異常(Status!=1)：`UpdateTime`會一直更新，應該是"異常"發生或更新狀態的時間。

## 桃園公車

> https://ebus.tycg.gov.tw/xmlptx/routes/alerts

- 正常(Status=1)：看起來沒問題。
- 異常(Status!=1)：目前沒有資料可以參考，需要來源確認一下`Alert.UpdateTime`的邏輯。

## 臺中公車

> https://citybus.taichung.gov.tw/ebus/xmlptx/routes/alerts

- 正常(Status=1)：目前沒有資料可以參考，需要來源確認一下`Alert.UpdateTime`的邏輯。
- 異常(Status!=1)：看起來沒問題。

## 新北公車

> https://tcgbusfs.blob.core.windows.net/ntpcbus/GetBusAlertList.gz

同"臺北公車"。

## 臺南公車

> http://ptx.2384.com.tw/PTX/xml/BusAlertList.xml

看起來沒問題。
-->
