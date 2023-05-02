Download Link: https://assignmentchef.com/product/solved-comp202-data-structures-and-algorithms-assignment-5
<br>
<h1>This programming assignment will test your knowledge and your implementation abilities of what you have learned in the Sorting parts of the class.</h1>

This homework must be completed individually. Discussion about algorithms and data structures are allowed but group work is not. Any academic dishonesty, which includes taking someone else’s code or having another person doing the assignment for you will not be tolerated. <strong>By submitting your assignment, you agree to abide by the Ko¸c University codes of conduct.</strong>

<h2>Description</h2>

This assignment requires you to implement various sorting algorithms. These algorithms include insertion sort, heap-sort, quick-sort, merge-sort and counting sort.

The files provided to you have comments that will help you with implementation.Keep the slides handy as they include the pseudo-codes for the algorithms. The file descriptions are below. Bold ones are the ones you need to modify and they are placed under the <em>code </em>folder, with the rest under <em>given</em>.

<ul>

 <li><em>java</em>: This file describes the abstract sorting class which the other sorting algorithms extend. It defines the sort method which is the primary function you should overwrite. It also has the swap and compare methods that you need to call in the concrete classes whereever applicable. Hint; not all algorithms utilize swap. It also has other utility methods which might be of use in debugging.</li>

 <li><em>java</em>: A wrapper class for the Java’s default sorting method. You can take a look if interested.</li>

 <li><em>java</em>: Implement the insertion sort algorithm in this file. Remember to use the swap and compare methods from the abstract parent class whereever applicable.</li>

 <li><em>java</em>: Implement the heap-sort algorithm in this file. Remember to use the swap and compare methods from the abstract parent class whereever applicable. Make sure to fill out the heapify method which will also be graded.</li>

 <li><em>java</em>: Implement the quick-sort algorithm in this file. Remember to use the swap and compare methods from the abstract parent class whereever applicable. Make sure to fill out the partition method which will also be graded. You have two options for this, either version which returns an indexPair object to return two indices or comment this out and uncomment the version which returns an integer.</li>

 <li><em>java</em>: Implement the merge-sort algorithm in this file. Remember to use the swap and compare methods from the abstract parent class whereever applicable. Make sure to fill out the merge method which will also be graded.</li>

 <li><em>java</em>: Implement the counting sort algorithm in this file. Note that you need to do this only for integers. You do not have to use any function from its parent in this class.</li>

 <li><em>java</em>: This file has a smaller main function which you can use to debug individual sorting algorithms. We suggest that you test your implementations here first.</li>

</ul>

1

<ul>

 <li><em>java</em>: This file grades your sorting implementations with different data distributions and data sizes. It checks aforementioned methods for certain algorithms and tests whether your implementations sort the data correctly. In addition to integers, doubles and strings are also utilizied. The code also checks for number of swaps and compares for three algorithms. Small implementation details might result in slightly different numbers. If you are getting sorted elements but swaps and compares do not match, make sure to finish the rest of the homework and come back to the issue.</li>

 <li><em>java</em>: This file has the code to generate data to test your implementations. Take a look at it if interested but you do not need to worry about it.</li>

</ul>


