# DSA(Data Structures and Algorithm):

## ALGORITHM:
### What is an Algorithm?
An algorithm is a set of well-defined instructions in sequence to solve a problem.

### Features of a Good Algo?
1. Input and output should be defined.
2. Each step in an algo should be clear and unambigous.
3. Algos should be most effective among many different ways to solve a problem.
4. Algos shouldn't include computer code.

### Algorithm Examples:
#### 1] Algorithm to find the largest among three numbers:
1. Start
2. Declare variables a,b and c.
3. Read the variables a,b and c.
4. If a>b
          If a>c
            Display a is the largest number.
          If b>c
            Display b is the largest number.
          Else
            Display c is the greatest number.
5. Stop

#### 2] Algorithm for fibonacci series till <=1000:
1. Start 
2. Declare variables first_term,second_term and temp. 
3. Initialize variables first_term ← 0 second_term ← 1 
4. Display first_term and second_term 
5. Repeat the steps until second_term ≤ 1000 
     5.1. temp ← second_term 
     5.2. second_term ← second_term + first_term 
     5.3. first_term ← temp 
     5.4. Display second_term 
6. Stop

### So, Why Learn Algorithms?
1. Makes your code scalable.
2. Time is precious, so if there is some way that we can conserve time then we should go for that solution(Time Management).
3. Memory is also precious/expensive(Space Management).
4.Efficiency of code.

### ASYMPTOTIC NOTATIONS(VVI):
They are the mathematical notations used to describe the running time of an algorithm when the input tends towards a particular value or a limiting value.
For example:
In Bubble Sort, when the input array is already sorted, the tme taken by the algorithm is linear i.e. the best case.
But when the input array is not at all sorted, the algorithm takes maximum time to sort the elements i.e. the worst case. 

There are mainly 3 Asymptotic Notations:
#### 1] BIG-O notation
Represents the uper bound of the running time of an algorithm. Thus it gives the worst-case complexity of the algorithm.

<img src="https://media.springernature.com/original/springer-static/image/chp%3A10.1007%2F978-1-4842-3988-9_1/MediaObjects/465726_1_En_1_Fig1_HTML.jpg" width="500">
          
#### 2] Omega notation:
Omega notation represents the lower bound of the running time of an algorithm. Thus, it provides the best case complexity of an algorithm.

<img src="https://cdn.kastatic.org/googleusercontent/LzlxDZW4-ShP9YIzsGub1VAg1etmCuIg4vI_bqL1DtBElj-IcixpXkuUrpJvKgQwjulxosf9NwEhaoFN3Cg5hlfS" width="500">

#### 3] Theta notation
Theta notation encloses the function from above and below. Since it represents the upper and the lower bound of the running time of an algorithm, it is used for analyzing the average-case complexity of an algorithm.

<img src="https://cdn.kastatic.org/googleusercontent/-wifqTWyEEUOT_GdHeDafyyALYYDLagxRL5N6Sb5UjUWfeU4UjF7b8_7fcLBUYVc-0fNKpr4Cf3jFdbRWjAHO_RQ" width="500">

