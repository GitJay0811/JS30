## 重點
```
  const wes = {
      name: 'Wes',
      age: 100,
      social: {
        twitter: '@wesbos',
        facebook: 'wesbos.developer'
      }
    };

    //結合兩物件(後蓋前)
    let wes2 = Object.assign({},wes)

    //如果複製的物件裡沒有function，用JSON.parse幾乎就可以深層複製了。
    //注意JSON.parse不能複製物件裡的function
    //JSON.stringify : 把物件轉字串("wes")
    //JSON.parse : 把字串轉物件({wes})
    let wes3 = JSON.parse(JSON.stringify(wes));
```