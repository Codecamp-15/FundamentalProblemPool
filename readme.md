[reference](https://www.youtube.com/watch?v=m55PTVUrlnA)

ex.

```js
// 1.ประกาศตัวแปร a เก็บค่า Boolean true

// 2. ประกาศตัวแปร b เก็บค่าตัวแปร a โดยให้เป็นค่า Boolean ค่าตรงข้าม
const b = !a
// 3. console.log ค่าตัวแปร b

// 4. ประกาศตัวแปร name เพื่อรับค่าชื่อตัวเอง
const name = "Stang"

// 5. ประกาศตัวแปล declareName เพื่อนำชื่อในตัวแปร name มาใส่ในข้อความ "My name is" และ console.log ตัวแปร declare name
const declareName = `My name is ${name}`


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

Exercise 3:
เมื่อประกาศตัวแปร number มีค่าเท่ากับ 5 จงสังเกตว่า การใช้งาน if-else ใน solution 1 และ solution 2 ให้ผลลัพธ์เหมือนหรือแตกต่างกันอย่างไร เพราะเหตุใด จงอธิบาย
const number = 5

//solution 1
if(number > 1 && number < 6){
  conseolg.log("case 1")
}else if (number > 7){
  console.log("case 2")
}else {
  console.log("case 3")
}

//solution 2

if(number > 1 && number < 6){
  conseolg.log("case 1")
}
if (number > 7){
  console.log("case 2")
}else {
  console.log("case 3")
}


Exercise 4:

const loging = true
const isAdmin = false
let name = null

if(login){
  if(isAdmin){
    name = "CC_15"
  }
}

console.log(name) // ผลลัพธ์คืออะไร


Exercise 5: จงเปรียบเทียบ if-else statement จากข้อ 4 ว่ามีการทำงานให้ผลลัพธ์เหมือนกันหรือไม่ อย่างไร

if (isAdmind && login) {
  name = "CC_15"
}


# Loop

# Function

# Object

# Array

# ES6
