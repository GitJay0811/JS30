## 重點
#### 1.
```
//以下結果都相同
let li = document.querySelectorAll('li')

let a = Array.from(li).map(item => item)
let b = [].map.call(li,item => item)
let c = [].map.apply(li,[item => item])
let d = [...li].map(item => item)
console.log(li,a,b,c,d)
```
#### 2. `let [min,sec] = time.split(":"); //5:43 => [5,43]` 
