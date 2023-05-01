Download Link: https://assignmentchef.com/product/solved-ccc-series
<br>
Write C Program

For a series Of numbers with n elements Xo, Xl,X2,

<ul>

 <li>Calculate mean g and variance var: g = — Var=— — g)</li>

 <li>Carry Out sorting: ascending or descending.</li>

</ul>

For the implementation in C applies:

<ol>

 <li>A function (name e.g., output) should be created for the output of the series of numbers. In addition to the call parameters for the series of numbers, the function output should have another call parameter: a pointer to a character string. The function output should first output this character string and then the series of numbers.</li>

 <li>A C function (name, e.g., statistics) should be created for the calculation of the mean and the variance of the series of numbers. I.e., the Statistics function calculates the mean and variance. The statistics function must not contain output via printf or the like.</li>

 <li>For the sorting of the series of numbers, a C function (name e.g., sorting) should be created, which among other things has a call parameter for the sorting order (ascending or descending). I.e., the Sort function sorts in ascending or descending order. The Sort function must not contain Output via or the like.</li>

</ol>

The following applies to the program:

<ol>

 <li>All variables should be local. Global variables may not be used.</li>

 <li>The fixed number series 4.31.2 2.4 3.5 5.2 9.8 3.1 should be used.</li>

 <li>The number series is to be output with the function Output. The character string for the output function should be “Unsorted:”. I.e. the output of the function should be: Unsorted: 4.31.2 2.4 etc.</li>

 <li>It is to be calculated with the function Statistics of the mean and the variance of the number series and output in the main program (main function).</li>

 <li>With the Sort function, the number series should be sorted (ascending or descending).</li>

 <li>The sorted number series should be output with the function Output. The character string for the output function should be “Sorted in ascending order:” or “Sorted in descending order:” (depending on the sort order). I.e. the Output Of the function should be sorted in ascending order: 1.2 2.4 3.1 etc. or sorted in descending order: 9.8 5.2 4.3 etc.</li>

</ol>

To test the program:

Hints:

<ul>

 <li></li>

 <li></li>

</ul>

Mean g -4.214 285, variance Var- 6.615 510.

Due to various effects (e.g., calculation accuracy), the last digits in the results may differ.

Sorted in ascending order: 1.2 2.4 3.13.5 4.3 5.2 9.8

Sorted in descending order: 9.8 5.2 4.3 3.5 3.12.41.2

The sum formula can be implemented with a for loop:

float

for 0=0;}

The function pow can be used to calculate the square of the variance:

e.g., for y = a2: y = pow (a, 2);

For the pow function, the header file math.h must be included: *include &lt;math.h&gt;

The bubble sort algorithm can be used for sorting. For the triangle exchange, the data type float or double must be used for the auxiliary variable the sort order can e.g., be controlled with the type of comparison of the two neighboring values v [0 and v [g + Il: &gt; is an order (e.g. ascending) and &lt;the other order (e.g. descending).

The sort order can also be entered by the user, e.g., + for ascending and – for descending. Possible solutions: scanf c”, &amp; sign); What is important here is the space before% or character = gg!fb (); Include header file <a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="b3d4c3f3dbc5dad2">[email protected]</a> #include


