1. Cho đoạn code sau:

```
var a = {},
    b = { key: 'b' },
    c = { key: 'c' };

a[b] = 123;
a[c] = 456;

console.log(a[b])
```

Kết quả nhận được là:

- [ ] 'b';
- [ ] 123
- [x] 456
- [ ] Không kết quả nào đúng.

2. Cho đoạn code sau:

```
console.log(false === '0');
```

Kết quả nhận được là:

- [ ] true;
- [x] false
- [ ] undefined
- [ ] 0

3. Cho đoạn code sau:

```
console.log(false == '0');
```

Kết quả nhận được là:

- [x] true;
- [ ] false
- [ ] undefined
- [ ] 0

4. Giá trị nhận được của đoạn mã dưới là:

```
console.log(typeof typeof 1)
```

- [ ] number
- [x] string
- [ ] boolean
- [ ] object

5. Kiểu dữ liệu của `NaN`?

- [x] number
- [ ] string
- [ ] boolean
- [ ] object

6. Giá trị x nhận được ở đoạn code dưới là

```
var x =  21;
var girl = function() {
  console.log(x);
  var x = 20;
}
girl()
```

- [] 21
- [] 20
- [] null
- [x] undefined

7. Giá trị x được ghi ra ở đoạn code dưới đây là:

```
(function(x) {
  return (function(y) {
    console.log(x)
  })(2)
})(1)
```

- [x] 1
- [] 2
- [] null
- [] undefined

9. Đoạn code dưới đây có kết quả là

```
console.log(1 + "2" + "2")
```

- [] undefined
- [] 5
- [x] "122"
- [] null

10. Cho array có giá trị là:

```
var a = [1, 2, 3, null, undefined, 4];
```

Giá trị nhận được khi `console.log(a.length)` là:

- [] 3
- [] 4
- [] 5
- [x] 6
