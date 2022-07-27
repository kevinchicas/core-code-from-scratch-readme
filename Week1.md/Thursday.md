*<center> <h2> Print special numbers/Exercise </h2> </center>*


Get even numbers from 0 to 100 using **for**

```assembly

for (let i = 1; i <= 100; i++) 
  {
    if (i % 2 == 0)
    { 
    console.log(i);
    }
  }
  ```

Get even numbers from 0 to 100 using **while**

```assembly

let i= 0;

while (i <= 100) {
  if (i % 2 == 0) {
    console.log(i);
}

i++
}
  ```

  Get even numbers from 0 to 100 using **do while**

```assembly

let i= 0;

do {
  if (i % 2 == 0) {
    console.log(i);
}

i++;
} while (i <= 100); 
  ```



---

*<center> <h2> Bad Code/Exercise </h2> </center>*

---

*<center> <h2> Bad Code 2/Exercise </h2> </center>*

```assembly
var n = 100;

if (n == 100) {
  console.log('This is a special number!');
}
else if (n < 1000 && n % 10 == 0 && n !=100){
console.log('This number is almost special');}

else {
  console.log('Just a regular number');
}
```

---