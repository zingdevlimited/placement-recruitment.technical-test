# Zing Dev Assessment Centre - Technical Test  
> If you need clarification on any questions, please ask one of our Developers.

## Question 1

Assume A, B, and C are boolean variables.
Explain the difference between `(A OR B) AND C` versus `A OR B AND C`

## Question 2

What is a good example of API documentation and why? Outline the key features of good API documentation in your answer.
Explain and justify your points in detail. Examples may be used to illustrate your points.

## Question 3

Assume that the two tables below are SQL tables on an SQL server.

**"People" Table**

| id  | firstName | lastName | rank       | shipName     | shipId (Foreign Key to Ship table) |
| --- | --------- | -------- | ---------- | ------------ | ---------------------------------- |
| 1   | Jean-Luc  | Picard   | Captain    | Enterprise   | 1                                  |
| 2   | Harry     | Kim      | Ensign     | Voyager      | 2                                  |
| 3   | Kathryn   | Janeway  | Captain    | Voyager      | 2                                  |
| 4   | Benjamin  | Sisko    | Captain    | Deep Space 9 | 3                                  |
| 5   | Deanna    | Troi     | Coucillor  | Enterprise   | 1                                  |
| 6   | William   | Riker    | Commander  | Enterprise   | 1                                  |
| 7   | Reginald  | Barclay  | Lieutenant | Prometheus   | 4                                  |


**"Ships" Table**

| id  | shipClass  | length | width | numberOfEngines |
| --- | ---------- | ------ | ----- | --------------- |
| 1   | Galaxy     | 400    | 300   | 2               |
| 2   | Intrepid   | 200    | 100   | 2               |
| 3   | Starbase   | 500    | 500   | 0               |
| 4   | Prometheus | 250    | 170   | 4               |


### 3a

Write an SQL query which would retrieve the firstName and lastName of all records with a rank of “Captain” ordered alphabetically by first name.

### 3b

Write an SQL query which would retrieve the shipName, shipClass, and numberOfEngines from a ship, ordered by length (largest to smallest).
What would the first result of this query be?

### 3c

What would you do to improve the structure of the data stored in the two SQL tables that appear above?

## Question 4

### 4a

Explain Inheritance in Object Oriented Programming (OOP) and when you would use inheritance. Examples may be used to illustrate your explanation.

### 4b

Explain Inversion of Control in Object Oriented Programming and when you would use Inversion of Control. Examples may be used to illustrate your explanation.

## Question 5

### 5a

What is "Big O" notation?

### 5b

What is the Big O of the function getFirstValueMoreThanFifty defined below:  
> Note: The following function is written in javascript. You may assume inputArray is an array of integers. Javascript indexes its arrays at zero

```js
function getFirstValueMoreThanFifty(inputArray)
{
  for (let i = 0; i < inputArray.length; i++)
  {
    element = inputArray[i];

    if (element > 50)
    {
      return element;
    }
  }

  return 0;
}
```

### 5c

If you were to call the function getFirstValueMoreThanFifty([1, 2, 5, 49, 50, 51]) (AKA where inputArray is equal to [1, 2, 5, 49, 50, 51]), what integer value would the function return?

## Question 6

Write a function 'in_fibonacci' that takes in one input: `int n` and returns a boolean value indicating whether n appears in the Fibonacci sequence, true if it does and false otherwise.  
You may use any language you're comfortable in, but please indicate the language used.

## Question 7

List and explain some techniques for making a web application more secure, and why you would implement these.  
Examples may be used to illustrate your explanation.

