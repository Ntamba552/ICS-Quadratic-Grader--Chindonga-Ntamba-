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
| *100* | A+             | [span_16](start_span)Yes[span_16](end_span)      |
| *84* | A              | [span_17](start_span)Yes[span_17](end_span)       |
| *65* | B+             | [span_18](start_span)Yes[span_18](end_span)       |
| *49* | D              | [span_19](start_span)Yes[span_19](end_span)      |
| *0* | D              | [span_20](start_span)Yes[span_20](end_span)      |
