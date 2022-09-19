
# HW1 EE538
## University of Southern California
## Instructor: Arash Saifhashemi

Please clone this repository, edit README.md to answer the questions, and fill up functions to finish the homework.

- Please find each question in a separate folder under [file](/file).
- For non-coding questions, fill out the answers in the README file.
- For coding questions, edit the files and check them in.
- For coding questions unless specified, you should add unit tests to the student_test.cc.
  We will clone and test your repo using your tests and some other tests (that are not provided). Your code should pass all of them.
- For submission, please push your answers to Github before the deadline.
- Deadline: Sep 19 by 12:00 pm (noon)
- Rubrics:
  
| Question | Points |
| -------- | ------ |
| 1        | 40     |
| 2        | 20     |
| 3        | 20     |
| 4        | 20     |
| 5        | 20     |
| 6        | 12     |

- Total: 132 points. 100 points is considered full credit.


See [cpp-template](https://github.com/ourarash/cpp-template) for help on installing bazel and debugging.

# Question 1 to 5
Coding question: please refer to [files](/files).

# Question 6
Please write down the worst case runtime complexity of the functions that you implement in this README file. 
For each case, please provide a reason.

In Question 1, the worst case runtime complexity is O(n). For Reverse(), the function needs to scan the input when reading it. For PlusOne(), the worst case is 2*n, and it is O(n), too.

In Question 2, the worst case runtime complexity is O(n^(1/2)). The function needs to try number from 2 to sqrt(n).

In Question 3, the worst case runtime complexity is O(n). The function needs to scan the whole string.

In Question 4, the worst case runtime complexity is O(n^3). The function needs to scan the 3D vector.

In Question 5, the worst case runtime complexity is O(n). The function have 4*n operations.# EE538
