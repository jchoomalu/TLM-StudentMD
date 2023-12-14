# Week 10 Intro To JavaScript

## Glossary Review
- Variable: A container for a value. The main building block for all programming 
- Declare: Creating a new variable (distinct from assignment) 
- Assignment: Assigning a value to a variable 
- Concatenation: The binding of multiple strings together using the + string operator 
- Interpolation: The process of injecting a variable directly into a string. 

## Glossary Concepts
- Operator: Symbols that are used to assign, compare, and perform operations 
- Conditional: An expression that evaluates to true or false, or a control flow statement that executes code 

## Learning Objective 
- Create conditional logic with if/else statements
- Implement variables, interpolation, and conditionals into the new-day-portfolio

## Operators


1. **Assignment operators** assign a value to a variable. 
        assign a variable (=)

        ```js 
        let color = 'magenta';
        ```

2. **String operators** combine strings. concatenation
        concatenate (+) 

        ```js
        let greeting = 'Hello ' + 'world!';
        ```

3. **Arithmetic operators** perform basic math. 
        Addition (+)
        Subtraction (-)
        Multiplication (*)
        Division (/)
        Modulus (%) - Returns the remainder of a division

        ```js
        let addNums = 2 + 2; // 4
        let subtractNums = 5 - 3 // 2
        let multilpyNums = 2 * 2; // 4
        let divideNums = 10 / 3; // 3.3333333333
        let remainder = 10 % 3; // 1
        ```

4. **Comparison operators** compare two values and return a true or false.
        Equal to (== or ===)
        Not equal to (!= or !==)
        Greater than (>)
        Less than (<) 
        Greater than or equal to (>=)
        Less than or equal to (<=)

        ```js
        let thisIsTruthy = "1" == 1; //true
        let thisIsFalsy = "3" === 3; //false
        let greater = 5 > 2; // true
        let lesser = 5 < 3; //false
        let greaterOrEqual = 5 >= 5; // false
        let lesserOrEqual = 5 <= 5; // true
        ``` 

5. **Logical operators** combine expressions and return a Boolean value of T or F
        AND (&&)
        OR (||)
        NOT (!)

        ```js
        let combinedExpressions = (3 <= 8) || (6 < 4); //true
        let flipFlop = !true // false
        ```

**Quiz Question** 

What is the difference between the double == and triple === and why is it important?


## Conditionals 

**`Conditionals are the primary way in which we allow our programs to make decisions. They help CONTROL THE FLOW of the program by by executing different blocks of code depending on whether a condition evalutes to true or false.`**

```js
if (expression) { 
statement; 
} else { 
other statement; 
} 
```

## Expression examples
```js
myNumber < 5
userCity === "Denver"
isTired //Boolean value
```

**`If the expression evaluates to true the statement inside the code block {} for that condition will run`**


**Consider this**
What do you think the use case is for conditionals?

**Now lets write some code!**

**Wrap up question**
What is the difference between the == and the === and why is it important? 
