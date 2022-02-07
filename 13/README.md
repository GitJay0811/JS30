## 重點
#### 1.因為滾輪每一小格都會觸發，所以用 debounce(閉包概念) 來提升效率。
####  `window.scrollY` : 現在網頁視窗最上面的位置。
#### `window.innerHeight` : 視窗的高度。
#### `arguments` : 不知道參數有幾個時，使用此變數。
#### `call`和`apply` : 指定function裡的this，功能一樣，差別在傳遞參數。
```
let b = {}
a.call(b,1,2,3) // call 像電話號碼，一個一個按
a.apply(b,[1,2,3]) //apply 一整包給
```