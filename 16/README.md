## 重點
#### 1.物件解構賦值
```
let obj = {
  website: "pjchender",
  country: "Taiwan"
}

let {website, country} = obj;
console.log(website);  // pjchender
console.log(country);  // Taiwan
```
#### 2.offsetX 和 offsetY 為滑鼠所在的容器位置開始算
#### 3.target : 滑鼠的目標，this : 事件監聽的目標
#### 4.`Math.floor` 無條件捨去小數
#### 5. -1~1 = (0~1) * 2 -1