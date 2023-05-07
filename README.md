Download Link: https://assignmentchef.com/product/solved-introduction-to-programming-languages-cecs130-lab-2
<br>
<strong> </strong>Read chapter 2 in your C book.

<ul>

 <li><strong>Programming assignment (100 pts): </strong>Write a computer program in C which will request the user to enter a number representing the amount of foreign currency he/she would like to exchange. Your program should output a foreign currency conversion table for <u>at</u> <u>least 6 different currencies</u>, showing how much of each type of foreign currency can be obtained for the amount the user enters.</li>

</ul>

The example below shows a foreign currency exchange table for <u>one unit</u> of foreign currency. Your program is interactive and so should work for any input amount from the user not just 1.00. In the example table, the number entered by the user is 1, and it shows that 1 USD is equal to 0.547525 GBP, while 1 GBP is equal to 2.11928 AUD and so forth.  If the user enters 2, your table should show how much 2 USD is in GBP, CAD, EUR, etc. along with how much 2 CAD would be in EUR, GBP, USD, etc, for each of the 6 currencies. The example uses real graphics not ASCII-art so it is ok if your table is not as visually pleasing.




<table width="440">

 <tbody>

  <tr>

   <td width="37"> </td>

   <td width="84">       USD</td>

   <td width="75">       GBP</td>

   <td width="84">       CAD</td>

   <td width="75">   EUR</td>

   <td width="84">       AUD</td>

  </tr>

  <tr>

   <td width="37"> </td>

   <td width="84"> </td>

   <td width="75"> </td>

   <td width="84"> </td>

   <td width="75"> </td>

   <td width="84"> </td>

  </tr>

  <tr>

   <td width="37"> </td>

   <td width="84">  1</td>

   <td width="75">  <a href="http://www.x-rates.com/d/USD/GBP/graph120.html">1.8264</a></td>

   <td width="84">  <a href="http://www.x-rates.com/d/USD/CAD/graph120.html">0.949938</a></td>

   <td width="75">   <a href="http://www.x-rates.com/d/USD/EUR/graph120.html">1.46849</a></td>

   <td width="84">   <a href="http://www.x-rates.com/d/USD/AUD/graph120.html">0.861801</a></td>

  </tr>

  <tr>

   <td width="37"> </td>

   <td width="84">  <a href="http://www.x-rates.com/d/GBP/USD/graph120.html">0.547525</a></td>

   <td width="75">   1</td>

   <td width="84">  <a href="http://www.x-rates.com/d/GBP/CAD/graph120.html">0.520114</a></td>

   <td width="75">   <a href="http://www.x-rates.com/d/GBP/EUR/graph120.html">0.80404</a></td>

   <td width="84">   <a href="http://www.x-rates.com/d/GBP/AUD/graph120.html">0.471857</a></td>

  </tr>

  <tr>

   <td width="37"> </td>

   <td width="84">  <a href="http://www.x-rates.com/d/CAD/USD/graph120.html">1.0527</a></td>

   <td width="75">  <a href="http://www.x-rates.com/d/CAD/GBP/graph120.html">1.92265</a></td>

   <td width="84">   1</td>

   <td width="75">  <a href="http://www.x-rates.com/d/CAD/EUR/graph120.html">1.54588</a></td>

   <td width="84">   <a href="http://www.x-rates.com/d/CAD/AUD/graph120.html">0.907218</a></td>

  </tr>

  <tr>

   <td width="37"> </td>

   <td width="84">  <a href="http://www.x-rates.com/d/EUR/USD/graph120.html">0.680967</a></td>

   <td width="75">   <a href="http://www.x-rates.com/d/EUR/GBP/graph120.html">1.24371</a></td>

   <td width="84">   <a href="http://www.x-rates.com/d/EUR/CAD/graph120.html">0.646876</a></td>

   <td width="75">   1</td>

   <td width="84">  <a href="http://www.x-rates.com/d/EUR/AUD/graph120.html">0.586858</a></td>

  </tr>

  <tr>

   <td width="37"> </td>

   <td rowspan="2" width="84">  <a href="http://www.x-rates.com/d/AUD/USD/graph120.html">1.16036</a></td>

   <td rowspan="2" width="75">  <a href="http://www.x-rates.com/d/AUD/GBP/graph120.html">2.11928</a></td>

   <td rowspan="2" width="84">   <a href="http://www.x-rates.com/d/AUD/CAD/graph120.html">1.10227</a></td>

   <td rowspan="2" width="75">  <a href="http://www.x-rates.com/d/AUD/EUR/graph120.html">1.70398</a></td>

   <td rowspan="2" width="84">   1</td>

  </tr>

  <tr>

   <td width="37"> </td>

  </tr>

  <tr>

   <td colspan="6" width="440">  <em>Friday, August 29, 2008</em></td>

  </tr>

 </tbody>

</table>










All exchange rates in your program must be current and coded as constants. Make sure you display a nice looking table using escape sequences and your ability to produce beautiful ASCII-art. You program <strong>MUST </strong>be bug-free and well commented (Including author information, program description, lab section, date, etc.)