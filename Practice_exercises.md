# JavaScript Practice Exercises

## 1. **JavaScript Basics & Variables**
1.1 Declare a variable `name` and assign it your name.

1.2	Declare a constant `PI` and assign it the value of 3.14159.

1.3	Swap the values of two variables `a = 5` and `b = 10` without using a third variable.

1.4	Convert a number to a string and a string to a number.

1.5	Check the type of `true`, `42`, `"hello"`, and `{}` using `typeof`.

## 2. **Data Types & Type Conversion**
2.1	What will `console.log(2 + "2")` output? Explain.

2.2	Convert `let num = "42.5"` to an integer and a float.

2.3	Check if `"123abc"` can be converted into a valid number.

2.4	Compare `==` and `===` with examples.

2.5	What will be the result of `console.log(Boolean(0), Boolean(1), Boolean(""), Boolean("hello"))`?

## 3. **String Manipulations**
3.1	Extract the word <u>`"JavaScript"`</u> from <u>`"I love JavaScript programming!"`</u>.

3.2	Convert <u>`"hello world"`</u> to uppercase and <u>`"HELLO WORLD"`</u> to lowercase.

3.3	Replace <u>`"JavaScript"`</u> with <u>`"Python"`</u> in the sentence **<u>`"I love JavaScript"`</u>**.

3.4	Check if the word <u>`"code"`</u> exists in <u>`"Learn to code with JavaScript"`</u>.

3.5	Reverse a given string <u>`"hello"`</u> to **<u>`"olleh"`</u>**.

## 4. **Functions**
4.1	Write a function to return the sum of two numbers.

4.2	Create a function that checks if a number is even or odd.

4.3	Write a function that takes a string and returns its length.

4.4	Define a function expression that multiplies two numbers.

4.5	Write an **arrow function** to find the square of a number.

## 5. **Function Scoping & Hoisting**
51. What will be the output of this code?
    
```
  console.log(x);
  var x = 5;
```
5.2 Explain the difference between `let`, `const`, and `var` in terms of scoping.

5.3 What will be the output of this function?
```
function test() {
    var a = 10;
    if (true) {
        var a = 20;
    }
    console.log(a);
}
test();
```

5.4 Explain the difference between function declarations and function expressions.

5.5 Rewrite the following function as an <u>arrow function</u>:
```
function greet(name) {
    return "Hello " + name;
}
```

## 6. **OBjects**
6.1 Create an object representing a student with properties `name`, `age`, and `grade`.

6.2 Add a method `getDetails` to the object that returns `"Name: John, Age: 20, Grade: A"`.

6.3 Write a function that returns the keys of an object.

6.4 Write a function that returns the values of an object.

6.5 Merge two objects `{a:1, b:2}` and `{c:3, d:4}`.

## 7. **Arrays**
7.1 Create an array of 5 programming languages.

7.2 Add an element at the beginning of an array.

7.3 Access the third element in an array.

7.4 Add an element `"Python"` to the end of an array.

7.5 Remove the first element from an array.

7.6 Find the index of `"JavaScript"` in `["Python", "JavaScript", "C++"]`.


## 8. **Array Methods**
8.1. Filter out even numbers from `[1,2,3,4,5,6]`.

8.2 Use `map()` to create a new array that doubles each number in `[1,2,3]`.

8.3 Use `reduce()` to sum up `[10, 20, 30]`.

8.4 Sort `[5,3,8,1,2]` in ascending order.

8.5 Check if every element in `[5, 10, 15, 20]` is greater than 4. return all elements greater than 4.

## 9. **Advanced Object & Array Manipulations**
9.1. Given `const person = { name: "Alice", age: 25, city: "NY" }`, extract `name` using **destructuring**.

9.2. Destructure the array `[10, 20, 30]` into `a`, `b`, and `c`.

9.3. Create a function that accepts an object and prints its properties.

9.4. Given `[{id:1, name:"John"}, {id:2, name:"Jane"}]`, find the object with `id = 2`.

9.5. Write a function that removes duplicates from `[1,2,3,3,4,4,5]`.

## 10. **Logical & Conditional Challenges**
10.1 Write a program to check if a number is prime. 

10.2 Find the largest number in `[10, 50, 30, 70, 20]`.

10.3 10.4 Write a program to count the occurrences of each letter in **<u>"banana"</u>**.

10.4 Write a program to count the occurrences of each letter in **<u>"pneumonoultramicroscopicsilicovolcanoconiosis"</u>**.

10.5 Write a function that generates a random number between 1 and 100

