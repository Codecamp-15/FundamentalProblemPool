[reference](https://www.youtube.com/watch?v=m55PTVUrlnA)

ex.

```js
// 1.ประกาศตัวแปร a เก็บค่า Boolean true

let a = true;
```

# Variable
Exercise 1: Declare and Initialize Variables
Declare a variable named myName using let and initialize it with your name.
Declare a variable named age using var and initialize it with your age.
Declare a variable named isLearning using const and initialize it with true.

Exercise 2: Variable Operations
Create two variables a and b using const and initialize them with 5 and 10 respectively.
Declare another variable sum using let and store the sum of a and b.

Exercise 3: Dynamic Types and Reassignment
Create a variable named unknown using let and set it to 5.
Reassign the value of unknown to "five".
Print the type of unknown using typeof.

```js
// 1. ประกาศตัวแปร name เก็บค่าชื่อของเรา
// 2. ประกาศตัวแปร age เก็บค่าอายุของเรา
// 3. ประกาศตัวแปร province เก็บค่าจังหวัดที่เราอยู่

let name = "Earth";
let age = "69";
let province = "Bangkok";
```

```js
// 1. ประกาศตัวแปร length เก็บค่าความยาวของพื้นที่
// 2. ประกาศตัวแปร width เก็บค่าความกว้างของพื้นที่
// 3. ประกาศค่าตัวแปร area เพื่อเก็บค่าพื้นที่ (ความยาว x ความกว้าง)

let length = 20;
let width = 100;
let area = length * width;
```

```js
// 1. ประกาศตัวแปร firstName เก็บค่าชื่อของเรา
// 2. ประกาศตัวแปร lastName เก็บค่านามสกุลของเรา
// 3. ประกาศตัวแปล fullName และนำ firstName และ lastName มารวมกัน

let firstName = "Code";
let lastName = "Camp";

let fullName = firstName + " " + lastName;
```

```js
// 1. ประกาศตัวแปรชื่อว่า counter และเก็บค่าเริ่มต้นเป็น 5
// 2. เพิ่มค่า counter 1
// 3. ลดค่า counter 2
// 4. ดูผลลัพท์ค่า counter

let counter = 5;
counter = counter + 1;
counter = counter - 2;
console.log(counter);
```

```js
// 1. รับ input เป็นสีที่เราชอบมากที่สุด
// 2. นำค่าสีที่ได้มา alert คำว่า "สีที่ชอบที่สุดคือ ..."

let favColor = prompt("ใส่สีที่ชอบที่สุด");
alert("สีที่ชอบที่สุดคือ" + " " + favColor);
```

# Condition
Exercise 1: Declare a variable named weather and initialize it with "sunny", "rainy", or "cloudy".
Write an if-elseif-else condition to print appropriate messages based on the value of weather.

Exercise 2: Create two variables username and password.
Write a nested if-else statement:
First, check if username is "admin".
If username is "admin", check if password is "password".
If both are true, print "Logged In".
If the password is incorrect, print "Wrong Password".
If the username is incorrect, print "Wrong Username".

```js
// 1. รับ input เป็นอุณหภูมิปัจจุบัน
// 2. ใช้ if-else ในการเช็คว่าอุณหภูมิเกิน 30 ไม่
// 3. หากเกินให้ alert คำว่า Higher 30 และ Lower or equal 30 หากต่ำกว่า

const currentTemp = prompt("กรุณาใส่อุณหภูมิปัจจุบัน");

if (Number(currentTemp) > 30) {
  alert("Higher 30");
} else {
  alert("Lower or equal 30");
}
```

```js
// 1. รับ input เป็นเลข 2 หลัก
// 2. ตรวจสอบว่าเลขตัวแรก สูงกว่าหรือต่ำกว่าเลขตัวที่สอง
// 3. หากสูงกว่าให้ alert เลข 1 ถ้าเท่ากันแสดงเลข 0 ถ้าตำแหน่งที่สองสูงกว่าให้แสดง -1

const inputNumber = prompt("กรุณาใส่เลขสองหลัก");

const firstNumber = Number(inputNumber.charAt(0));
const secondNumber = Number(inputNumber.charAt(1));

if (firstNumber > secondNumber) {
  alert("1");
} else if (firstNumber === secondNumber) {
  alert("0");
} else {
  alert("-1");
}
```

```js
// 1. รับ input เป็นคะแนน 0 - 100
// 2. ตรวจสอบก่อนว่าใส่ค่ามาถูกต้องหรือไม่
// 3. ตรวจสอบว่า คะแนนที่กรอกขึ้นมาได้เกรดอะไร
// 4. โดยใช้ condition ตามนี้ >= 80 A, >= 70 B, >= 60 C, >=50 D , < 50 F

const myScore = Number(prompt("กรุณาใส่คะแนน"));

if (!isNaN(myScore) && myScore >0 && myScore < 100) {
  if (myScore >= 80) {
    alert("A");
  } else if (myScore >= 70) {
    alert("B");
  } else if (myScore >= 60) {
    alert("C");
  } else if (myScore >= 50) {
    alert("D");
  } else {
    alert("F");
  }
}else {
    alert("ใส่คะแนนไม่ถูกต้อง")
}
```

# Loop

# Function

# Object

# Array

# ES6
