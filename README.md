Download Link: https://assignmentchef.com/product/solved-cpt-s-350-homework-3
<br>






<ol>

 <li>(easy) Write an algorithm that selects both the maximal element and the minimal element from an array <em>A </em>of <em>n </em>elements, using only 1<em>.</em>5·<em>n </em></li>

 <li>(not so easy) The algorithm <em>S</em>(<em>A,n,i</em>) selects all the <em>j</em>-th smallest elements (with <em>j </em>≤ <em>i</em>) from an array <em>A </em>of <em>n </em>elements, by using linearselect to select each of the <em>j</em>-th smallest elements (with <em>j </em>≤ <em>i</em>). Clearly, one could also implement <em>S </em>alternatively as <em>T</em>(<em>A,n,i</em>), which first sort <em>A </em>(on average-case and on worstcase, the sorting takes time <em>O</em>(<em>n</em>log<em>n</em>) using mergesort) and then select the first <em>i </em> Please compare the average-case complexities of the two algorithms; i.e., For the average-case complexities, under what conditions (on the choices for <em>i</em>), <em>S </em>is better than <em>T </em>or vice versa.</li>

 <li>(hard) In class, we have demonstrated the worst case complexity analysis for linearselect where each group has <em>k </em>= 5 numbers. Please show the worst case complexities for <em>k </em>= 3 and <em>k </em>= 7.</li>

 <li>(hard) Let ilselect(<em>A,n,i</em>) be an algorithm that selects the <em>i</em>-smallest from an array <em>A </em>with <em>n </em> It works as follows: ilselect(<em>A,n,i</em>){ <em>r</em>=partition(<em>A,</em>1<em>,n</em>);</li>

</ol>

//test if <em>A</em>[<em>r</em>] is the element to be selected if <em>i </em>== <em>r</em>, return <em>A</em>[<em>r</em>];

//test if quickselect from the low-part if <em>i &lt; r</em>, return quickselect(<em>A,</em>1<em>,r </em>− 1<em>,i</em>);

//test if linearselect from the high-part if <em>i &gt; r</em>, return linearselect(<em>A,r </em>+ 1<em>,n,i </em>− <em>r</em>);

}

That is, the algorithm runs quickselect on the low-part or runs linear select on the high-part. Show the worst-case complexity and the average complexity of the algorithm.

<ol start="5">

 <li>We use 5com to denote an operation that sorts 5 numbers. Show theminimal number of 5com operations that one need to sort <em>n </em>distinct numbers.</li>

</ol>

1