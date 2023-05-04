Download Link: https://assignmentchef.com/product/solved-cs524-homework-9-integer-programs
<br>



<ol>

 <li><strong>V oting. </strong>Governor Blue of the state of Berry is attempting to get the state legislator to gerrymander Berry’s congressional districts. The state consists of ten cities, and the numbers of registered Republicans and Democrats (in thousands) in each city are shown below</li>

</ol>

<table width="0">

 <tbody>

  <tr>

   <td width="42">C ity</td>

   <td width="87">R epublicans</td>

   <td width="79">Democrats</td>

  </tr>

  <tr>

   <td width="42">1</td>

   <td width="87">80</td>

   <td width="79">34</td>

  </tr>

  <tr>

   <td width="42">2</td>

   <td width="87">60</td>

   <td width="79">44</td>

  </tr>

  <tr>

   <td width="42">3</td>

   <td width="87">40</td>

   <td width="79">44</td>

  </tr>

  <tr>

   <td width="42">4</td>

   <td width="87">20</td>

   <td width="79">24</td>

  </tr>

  <tr>

   <td width="42">5</td>

   <td width="87">40</td>

   <td width="79">114</td>

  </tr>

  <tr>

   <td width="42">6</td>

   <td width="87">40</td>

   <td width="79">64</td>

  </tr>

  <tr>

   <td width="42">7</td>

   <td width="87">70</td>

   <td width="79">14</td>

  </tr>

  <tr>

   <td width="42">8</td>

   <td width="87">50</td>

   <td width="79">44</td>

  </tr>

  <tr>

   <td width="42">9</td>

   <td width="87">70</td>

   <td width="79">54</td>

  </tr>

  <tr>

   <td width="42">10</td>

   <td width="87">70</td>

   <td width="79">64</td>

  </tr>

 </tbody>

</table>

Berry has ve congressional representatives. To form the ve congressional districts, cities must be grouped together according to the following restrictions:

Districts cannot subdivide cities; all voters in a city must be in the same district.

Each district must contain between 150,000 and 250,000 voters (there are no independent voters).

Governor Blue is a Democrat. Assume 100% voter turnout and that each voter always votes according to their registered party. Formulate and solve an optimization problem to help Governor Blue maximize the number of congressional districts that have a Democratic majority.

<ol start="2">

 <li><strong>The Queens problem. </strong>You are given a standard 8 8 chess board. The following problems involve placing queens on the board such that certain constraints are satised. For each of the following problems, model the optimization task as an integer program, solve it, and show what an optimal placement of queens on the board looks like.

  <ol>

   <li>Find a way to place 8 queens on the board so that no two queens threaten each other. We say that two queens <em>threaten </em>each other if they occupy the same row, column, or diagonal. Show what this placement looks like.</li>

   <li>Repeat part (a) but this time nd a placement of the 8 queens that has point symmetry. In other words, nd a placement that looks the same if you rotate the board 180 .</li>

  </ol></li>

</ol>

<strong>) </strong>What is the smallest number of queens that we can place on the board so that each empty cell is threatened by at least one queen? Show a possible optimal placement.

<ol>

 <li><strong>d) </strong>Repeat part (c) but this time nd a placement of the queens that also has point symmetry. Does the minimum number of queens required change? Show a possible optimal placement.</li>

</ol>

<ol start="3">

 <li><strong>Relay Race. </strong>A new running team is planning for a 5 400 meters relay race. The team coach Fannie has decided that the following ve people will run the race: Alice, Bob, Cindy, David and Elisa. However, Fannie has not yet decided the order in which they will run. The average time for each of them to nish running 400 metres are 82<em>:</em>5<em>s; </em>77<em>:</em>1<em>s; </em>81<em>:</em>3<em>s; </em>74<em>:</em>9<em>s; </em>80<em>:</em>6<em>s</em>, respectively. In the taking-over zone, the runner who just nished must pass the baton to the next runner. The time it takes to pass the baton depends on the runners, and are listed for each combination of runners in seconds in the table below (the column gives the name of the runner who is passing the baton, and the row gives the name of the runner who receives the baton).</li>

</ol>

<table width="0">

 <tbody>

  <tr>

   <td width="173">Taking-over time (seconds)</td>

   <td width="46">A lice</td>

   <td width="40">B ob</td>

   <td width="52">C indy</td>

   <td width="51">David</td>

   <td width="45">E lisa</td>

  </tr>

  <tr>

   <td width="173">A lice</td>

   <td width="46">0</td>

   <td width="40">1.1</td>

   <td width="52">1.3</td>

   <td width="51">1.9</td>

   <td width="45">2.1</td>

  </tr>

  <tr>

   <td width="173">B ob</td>

   <td width="46">1.2</td>

   <td width="40">0</td>

   <td width="52">1.7</td>

   <td width="51">1.0</td>

   <td width="45">1.8</td>

  </tr>

  <tr>

   <td width="173">C indy</td>

   <td width="46">1.7</td>

   <td width="40">1.4</td>

   <td width="52">0</td>

   <td width="51">0.9</td>

   <td width="45">1.7</td>

  </tr>

  <tr>

   <td width="173">David</td>

   <td width="46">2.1</td>

   <td width="40">0.8</td>

   <td width="52">1.6</td>

   <td width="51">0</td>

   <td width="45">2.4</td>

  </tr>

  <tr>

   <td width="173">E lisa</td>

   <td width="46">1.5</td>

   <td width="40">1.2</td>

   <td width="52">1.9</td>

   <td width="51">2.3</td>

   <td width="45">0</td>

  </tr>

 </tbody>

</table>

The team is using a special baton to track their performance during the race. This baton is quite expensive, and Fannie is worried that one of the runners might loose it. Therefore, Fannie takes care of bringing the baton to the race. She gives the baton to the rst runner before the start of the race and gets it back from the last runner when the race is over (the time it takes for Fannie to give and receive the baton is not counted as part of the racing time).

Please help Fannie decide the order of the ve runners. What is the optimal runner sequence? What is the optimal total time for this race?