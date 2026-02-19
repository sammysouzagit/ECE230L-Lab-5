# Lab 05 - Combinatorial Logic

In this lab, you’ve learned real world applications of digital logic, as well
as how to assemble your own Verilog modules. In addition, you’ve learned how
the constraints file maps your inputs and outputs to real pins on the FPGA.

## Rubric

| Item | Description | Value |
| ---- | ----------- | ----- |
| Summary Answers | Your writings about what you learned in this lab. | 25% |
| Question 1 | Your answers to the question | 25% |
| Question 2 | Your answers to the question | 25% |
| Question 3 | Your answers to the question | 25% |

## Name
Eric Harris and Sammy Souza
## Lab Summary
In this lab we built separate circuit blocks and showed how those blocks could
be implemented in series to build a more complex circuit from those smaller blocks 
## Lab Questions

### 1 - Explain the role of the Top Level file.

### 2 - Explain the function of the Constraints file.
The constraints file maps the variable names for inputs and outputs to the physical
pins on the FPGA
### 3 - Was the selection of Minterm and Maxterm correct for each circuit? What would you have chosen?
Using maxterms for circuit A reduced the cicuit to only depend on A and D, so I believe that
was the correct choice there.
For circuit B, both minterms and maxterms would have resulted in three two input groups, but
the sum of products form is easier to read in some cases, so I believe that was also the
correct choice.

