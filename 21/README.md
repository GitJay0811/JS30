## 重點
```
1. 獲取現在位置，只抓取一次。
navigator.geolocation.getCurrentPosition((data) =>{})


2. 獲取位置，會依照位置改變一直抓取(持續)。
navigator.geolocation.watchPosition((data) => {})

兩者都會有成功和失敗的 callback
```