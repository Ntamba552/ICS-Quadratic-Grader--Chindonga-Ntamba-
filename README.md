# 📊 ICS-Quadratic-Grader-<YourSurname-YourFirstname>

## Project Description
This is a single-file web application (index.html) created for the ICT251 Web Technologies assignment. It contains two functional tools:
1. A *Quadratic Equation Solver* to find the discriminant and roots of $ax^2 + bx + c = 0$.
2. [span_14](start_span)A *Grade Converter* to convert a numeric score (0-100) to a letter grade based on the specified university scale[span_14](end_span).

## How to Run
This is a single-file application. To run it:
1. *Clone* or *Download* this repository.
2. *Double-click* the index.html file. [span_15](start_span)It will open and run directly in any modern web browser without needing a web server[span_15](end_span).

## Test Cases

### A. Quadratic Solver ($a=1, b=5, c=6$)
* *$a$*: 1
* *$b$*: 5
* *$c$*: 6
* *Expected Result*: $D=1$. Two distinct real roots: $x_1=-2.0000$, $x_2=-3.0000$.

### B. Grade Converter
| Input Score | Expected Grade | Required Edge Case? |
|-------------|----------------|---------------------|
| *100* |         A+                            Yes    
| *84* |         A                              Yes      
| *65* |         B+                             Yes       
| *49* |        D                               Yes     
| *0* |         D                                Yes
