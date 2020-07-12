

```javascript
Number
```




    [Function: Number]




```javascript
Number.prototype.add = function (x){return x+this}
```




    [Function]




```javascript
const five = Number(5);
five.add(5)
```




    10




```javascript
const addFunc = Number.prototype.add
```


```javascript
new Number(5).add(3)
```




    8




```javascript
addFunc.call(Number(5),3)
```




    8




```javascript
addFunc.apply(Number(5),[3])
```




    8




```javascript
new Date()
```




    2020-05-06T21:51:46.454Z




```javascript
addFunc.bind(Number(5))(3)
```




    8


