# ja-lab-12
### Lab12 Dynamic Type: Fundamental3
- จากโค้ดด้านล่างให้เขียนคำสั่งเพื่อแปลง a, b และ c ให้เป็น Boolean แล้วเก็บไว้ในตัวแปร d, e และ f ตามลำดับ
- ให้ใช้คำสั่ง console.log เพื่อแสดงค่าตัวแปร d, e และ f 
- ผลลัพธ์ที่ได้เป็นอะไรบ้าง และเพราะอะไร
- หริณ มาเบ้า มิก

```JavaScript
let a = undefined;
let b = ' ';
let c = !b;
```
```shell
Result
d = false (เป็น undefined หรือ 0 จะได้ค่า false)
e = true (ช่องว่าง ถือว่ามีค่าเป็นตัวอักษร จึงได้ true)
f = false (b = true ใส่! จึงกลายเป็น not true = false)
```
