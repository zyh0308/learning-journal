# Operators and Loops # 

#### Decisions and Loops ####

Looking at a flowchart (for all but the most basic scripts), the code can take more than one path, which means the browser runs different code in different situations. In this chapter, you will learn how to create and control the flow of data in your scripts to handle different situations.

- Evaluation: You can analyze values in your scripts to determine whether or note they match expected results.
- Decisions: Using the results of evaluations, you can decide which path your script should go down
- Loops: There are also many occasions where you will want to perform the same set of steps repeatedly.

**Evaluating conditions& conditional statement** 

There are two components to a decision: 
1. An expression is evaluated, which returns a value
2. A conditional statement says what to do in a given situation.


**Comparison operators: evaluating conditions

- == is equal to: This operators compares two valus( numbers,strings,or Booleans) to see if they are the same.
- != is not equal to : This operator compares two valus (numbers,strings,or Booleans) to see if they are not the same
- === is strict equal to: This operator compares two valus to check that both the data type and value are the same. 
- !== is strict not equal to: This operator compares two valus to check that both the data type and value are not the same
- > is greater than: This operator checks if the number on the left is greater than the number on the right
- < is less than: This operator checks if the number on the left is less than the number on the right
- >= is greater than or equal to: This operator checks if the number on the left is greater than or equal to the number on the right
- <= is less than or equal to: This operator checks if the number on the left is less than or equal to the number on the right

**Structuring Comparison Operators**

In any condition, there is usually one operator and two operands. The operands are placed on each side of the operator. They can be values or variables. You often see expressions enclosed in brackets.

**Switch Statements**

A switch statement starts with a variable called the switch value. Each case indicates a possible value for this variable and the code that should run if the variable matches that value.

1. IF... ELSE
  - There is no need to provide an el se option. (You can just use an if statement.)
 -  With a series of i f statements, they are all checked even if a match has been found (so it performs more slowly than switch).
 
2. Switch
  - You have a default option that is run if none of the cases match.
  - If a match is found, that code is run; then the break statement stops the rest of the switch statement running (providing better performance than multiple i f statements).
  

#### Loops ####

Loops check a condition. If it returns ture, a code block will run. Then the condition will be checked again and if it still renturn true, the code block will run again. It repeats until the condition returns false. 

1. **For**:If you need to run code a specifc number of times, use a for loop. 
2. **While**: If you dont know how many time the code should run, you can use a while loop. 
3. **Do While** : They do...while loop is very similar to the wile loop, but has one key differnce: it will always run the statment inside the curly braces at least once, even if the condition evaluates to false. 

