Download Link: https://assignmentchef.com/product/solved-csc349-assignment-2-divide-and-conquer
<br>
A “divide and conquer” algorithm is one that divides a problem into smaller subproblems, solves those subproblems, and then combines the “sub-solutions” into a solution to the original problem. In this assignment, you’ll apply the divide and conquer approach to solve two variations on a problem.

<strong>Deliverables:</strong>

<strong>GitHub Classroom: </strong><a href="https://classroom.github.com/a/1jevVm_6">https://classroom.github.com/a/1jevVm_6</a>

<strong>Required Files:                    </strong>compile.sh, run.sh

<strong>Optional Files:                           </strong>*.py, *.java, *.clj, *.kt, *.js, *.sh

<h1>Part 1: Finding the Singleton Element</h1>

A <em>singleton </em>is a single item, as opposed to two (or more) items grouped together, as in the “singleton pattern”, describing an object that may only be instantiated once, or a “singleton set”, a set containing only one element.

Consider the following problem: you are given a sorted sequence of integers. Within this sequence, one and only one element is unique; the other elements are all duplicated once. For example:

(−2<em>,</em>−2<em>,</em>5<em>,</em>5<em>,</em>12<em>,</em>12<em>,</em>67<em>,</em>67<em>,</em>72<em>,</em>80<em>,</em>80)

In your programming language of choice per Assignment 1, implement an algorithm to find that lone, unique, singleton element. In the example above, your algorithm should return <sub>72</sub>.

Your program must accept as a command line argument the name of a file containing a sequence as described above, then print to stdout the singleton element. For example:

&gt;$ ./compile.sh

&gt;$ ./run.sh in1.txt

72

Your program will be tested using diff, so its printed output must match <em>exactly</em>.

As you solve this problem, recall that there are two broad types of divide and conquer algorithms: those that look like binary search and those that look like merge sort. Which of those approaches will lead to a more efficient algorithm for this problem?

<h1>Part 2: Dealing with Multiple Copies</h1>

Consider the following generalization of the problem: you are given a sorted sequence of integers. Within this sequence, one and only one element is unique; the other elements are duplicated <em>at least </em>once. For example:

(−2<em>,</em>−2<em>,</em>5<em>,</em>5<em>,</em>5<em>,</em>67<em>,</em>67<em>,</em>72<em>,</em>80<em>,</em>80<em>,</em>80<em>,</em>80)

Does this alteration affect your algorithm? If so, write new pseudocode accordingly, however, <em>do not </em>adjust your implementation to match — your program need only solve the original variation of the problem.

1