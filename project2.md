[Back to Portfolio](./)

Sudoku Puzzle Validator
=======================

-   **Class: Operating Systems (CSCI 431)** 
-   **Grade: A** 
-   **Language(s): C** 
-   **Source Code Repository:** [mdstargel/soduku-puzzle-validator](https://github.com/mdstargel/soduku-puzzle-validator)  
    (Please [email me](mailto:mdstargel@csustudent.net?subject=GitHub%20Access%20-%20Sudoku%20Project) to request access.)
    
## Project description

This program reads in a sudoku board from a text file and incorporates it into a 9x9 matrix. The program then creates 11 variations of the struct for row and column information. Next the program creates the pthreads and calls the pthread functions. The functions check if each row, column and 3x3 subgrid (as determined in the struct) is valid (contains all numbers 1-9). If it is valid, the function updates the global array valid to read 1. If any row, column or 3x3 subgrid is not valid then the function updates the global array valid to read 0. Once all threads are finished and joined, a loop iterates through valid to check for 1s. If all elements are 1s, print out the "is Solved" statement and exit. If there is a 0, program prints out the "NOT Solved" statement and ends the program.

## How to compile and run the program

How to compile (if applicable) and run the project.

```bash
cd ./project
python setup.py
```

If the programming language does not require compilation, the update the heading to be “How to run the program.” If your application is deployed on a remote service, including instructions on how to deploy it.

## UI Design

"A Sudoku puzzle uses a 9 × 9 grid in which each column and row, as well as
each of the nine 3 × 3 subgrids, must contain all of the digits 1 · · · 9. Figure
4.19 presents an example of a valid Sudoku puzzle. This project consists of
designing a multithreaded application that determines whether the solution to
a Sudoku puzzle is valid. There are several different ways of multithreading this application. One
suggested strategy is to create threads that check the following criteria:
• A thread to check that each column contains the digits 1 through 9
• A thread to check that each row contains the digits 1 through 9
• Nine threads to check that each of the 3 × 3 subgrids contains the digits 1
through 9
This would result in a total of eleven separate threads for validating a
Sudoku puzzle. However, you are welcome to create even more threads for
this project. For example, rather than creating one thread that checks columns, you could create nine separate threads and have each of them check
one column."



![screenshot](images/dummy_thumbnail.jpg)  
Fig 1. The launch screen

![screenshot](images/dummy_thumbnail.jpg)  
Fig 2. Example output after input is processed.

![screenshot](images/dummy_thumbnail.jpg)  
Fig 3. Feedback when an error occurs.

## 3. Additional Considerations

Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. 

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

[Back to Portfolio](./)
