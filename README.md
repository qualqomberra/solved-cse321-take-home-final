Download Link: https://assignmentchef.com/product/solved-cse321-take-home-final
<br>
<strong>Q1.  </strong>Suppose that you are given an array of letters and you are asked to find a subarray with maximum length having the property that the subarray remains the same when read forward and backward. Design a dynamic programming algorithm for this problem. Provide the recursive formula of your algorithm and explain the formula. Provide also the pseudocode of your algorithm together with its explanation. Analyze the computational complexity of your algorithm as well. Implement your algorithm as a Python program. <strong>(20 points) </strong>




Let <em>A x x</em>= ( <sub>1</sub>, <sub>2</sub>,       , <em>x</em><em><sub>n</sub></em>) be a list of <em>n</em> numbers, and let <em>a b</em><sub>1 1</sub>, ,  ,<em>a b</em><em><sub>n</sub></em>, <em><sub>n </sub></em> be <em>n</em> intervals with

1  <em>a b n</em><em><sub>i i </sub></em>, for all 1 <em>i n </em>. Design a divide-and-conquer algorithm such that for every interval  <em>a b</em><em><sub>i </sub></em>, <em><sub>i </sub></em>, all values <em>m</em><em><sub>i </sub></em>= min<em>x</em><em><sub>j </sub></em>| <em>a</em><em><sub>i </sub></em> <em>j b</em><em><sub>i</sub></em> are simultaneously computed with an overall complexity of

<em>O n</em>( log( ))<em>n </em>.  Express your algorithm as pseudocode and explain your pseudocode. Analyze your algorithm, prove its correctness and its computational complexity. Implement your algorithm using Python. <strong>(20 points) </strong>Suppose that you are on a road that is on a line and there are certain places where you can put advertisements and earn money. The possible locations for the ads are x<sub>1</sub>, x<sub>2</sub>, …, x<sub>n</sub>. The length of the road is M kilometers. The money you earn for an ad at location x<sub>i</sub> is r<sub>i</sub> &gt; 0. Your restriction is that you have to place your ads within a distance more than 4 kilometers from each other. Design a dynamic programming algorithm that makes the ad placement such that you maximize your total money earned. Provide the recursive formula of your algorithm and explain the formula. Provide also the pseudocode of your algorithm together with its explanation. Analyze the computational complexity of your algorithm as well. Implement your algorithm as a Python program.

<strong> </strong>

A group of people and a group of jobs is given as input. Any person can be assigned any job and a certain cost value is associated with this assignment, for instance depending on the duration of time that the pertinent person finishes the pertinent job. This cost hinges upon the person-job assignment. Propose a polynomial-time algorithm that assigns exactly one person to each job such that the maximum cost among the assignments (not the total cost!) is minimized. Describe your algorithm using pseudocode and implement it using Python. Analyze the best case, worst case, and average-case performance of the running time of your algorithm. <strong>(</strong>




<strong> </strong>

Unlike our definition of inversion in class, consider the case where an inversion is a pair i &lt; j such that x<sub>i</sub> &gt; 2 x<sub>j</sub> in a given list of numbers x<sub>1</sub>, …, x<sub>n</sub>. Design a divide and conquer algorithm with complexity O(n log n) and finds the total number of inversions in this case. Express your algorithm as pseudocode and explain your pseudocode. Analyze your algorithm, prove its correctness and its computational complexity. Implement your algorithm using Python. <strong>(20 points) </strong>

<strong> </strong>