### Hi there 👋

<!--
**ChoYeSeul/ChoYeSeul** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

``` javascript
  can write js
```

### REACT 화면 밑 콤마 생김

```
 // index.js에서 콤마 없애기
```

### localStorage

```
localStorage.setItem('searchKeyword', JSON.stringify(arr)); // setItem - 아이템 보내기, JSON.stringify를 통해 문자열로 보내주기
JSON.parse(localStorage.getItem('searchKeyword')) // getItem - 아이템 받기, JSON.parse를 사용해 한번 까기
```

### 오브젝트 머리에 데이터 넣기
```
    let productData = {
        product_id: product?.product_id,
        product_img: product?.product_img,
        product_price: product?.product_price,
        product_sale_rate: product?.product_sale_rate,
        product_Kname: product?.product_Kname,
        sale_price: product?.sale_price,
        count: 1,
        options: {
            optionList: {},
            optId: optionIdArr,
            product: {
                product_id: product?.product_id,
                product_sale_rate: product?.product_sale_rate,
                product_price: product?.product_price,
            },
        },
    };

    productData.options.optionList[product?.product_id] = optionArr;
```
