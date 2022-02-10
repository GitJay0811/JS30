## 重點
#### 1. localStorage 主要兩個功能
+ 取資料`localStorage.getItem('items')`
+ 送資料`localStorage.setItem('items', JSON.stringify(items));`
#### 2. 在form表單中，最好用屬性選取器[]。
#### 3. `.reset()` : 把表單裡的元素全部重置為默認值。
```
  //只能用在form表單上
  document.querySelector('form').reset();

  //不可用在input上
  document.querySelector('input').reset();
```