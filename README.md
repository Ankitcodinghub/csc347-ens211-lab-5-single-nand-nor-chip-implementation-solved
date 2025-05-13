# csc347-ens211-lab-5-single-nand-nor-chip-implementation-solved
**TO GET THIS SOLUTION VISIT:** [CSC347-ENS211 Lab 5-Single NAND/NOR Chip Implementation Solved](https://www.ankitcodinghub.com/product/csc347-ens211-lab-5-single-nand-nor-chip-implementation-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;94105&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSC347-ENS211 Lab 5-Single NAND\/NOR Chip Implementation Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
<strong>Lab </strong><strong>5 Single NAND/NOR Chip Implementation</strong>

<ol>
<li><strong>Introduction </strong></li>
</ol>
NAND and NOR are universal gates and are preferred over AND or OR gates in logic design and chip fabrication. In this lab, the student will design, minimize and implement logic function using single NAND/NOR chip, i.e., you only need one chip on the board to build a circuit. Minimizing the number of chips can increase circuit reliability and reduce power consumption and system size.

&nbsp;

<ol start="2">
<li><strong>Components needed:</strong> <strong><u>note that 7402 chip has a different layout from 7400 chip.</u></strong></li>
</ol>
&nbsp;

1 — 74HC<strong>00</strong> Quad 2-input NAND gate &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1 — 74HC<strong>02</strong> Quad 2-input NOR gate

&nbsp;

<ol start="3">
<li><strong>All NAND Gate Implementation</strong></li>
</ol>
You are to build a circuit to implement the following function:

<strong>F = AB + BC’</strong>

<ul>
<li>Derive the truth table for the function, and draw the logic diagram using AND, OR and NOT gates:</li>
</ul>
&nbsp;

<table>
<tbody>
<tr>
<td width="55">A B C</td>
<td>AB</td>
<td>BC’</td>
<td>F</td>
</tr>
<tr>
<td width="55">0 0 0</td>
<td>0</td>
<td>0</td>
<td>0</td>
</tr>
<tr>
<td width="55">0 0 1</td>
<td>0</td>
<td>0</td>
<td>0</td>
</tr>
<tr>
<td width="55">0 1 0</td>
<td>0</td>
<td>1</td>
<td>1</td>
</tr>
<tr>
<td width="55">0 1 1</td>
<td>0</td>
<td>0</td>
<td>0</td>
</tr>
<tr>
<td width="55">1 0 0</td>
<td>0</td>
<td>0</td>
<td>0</td>
</tr>
<tr>
<td width="55">1 0 1</td>
<td>0</td>
<td>0</td>
<td>0</td>
</tr>
<tr>
<td width="55">1 1 0</td>
<td>1</td>
<td>1</td>
<td>1</td>
</tr>
<tr>
<td width="55">1 1 1</td>
<td>1</td>
<td>0</td>
<td>1</td>
</tr>
</tbody>
</table>
&nbsp;

<ul>
<li>Convert the circuit diagram to <strong>all NAND gates implementation.</strong></li>
</ul>
<strong>&nbsp;</strong>

<ul>
<li>Circuit construction on Tinkercad (DO NOT tear down the circuit after you finished this step.)</li>
</ul>
&nbsp;

Based on the diagram in (b), build the circuit using one <strong>7400</strong> chip. DIP switches will be used to supply all three input logic levels A, B and C, and a LED will be used to provide the F output.

<ul>
<li>Make a copy of the starter kit from <a href="https://www.tinkercad.com/things/19XqriP2dMF">https://www.tinkercad.com/things/19XqriP2dMF</a> and rename the copy as “Lab 5 Single Chip Implementation” on Tinkercad Circuits dashboard.</li>
<li>Connect the NAND gates according to the logic diagram from Step (b).</li>
<li>Connect the inputs (A, B, C) to three switches, and the output F to a LED.</li>
<li>Press “Start Simulation”.</li>
<li>Apply all eight combinations of logic LOW and HIGH levels to the three gate inputs using the DIP switches. Observe if the circuit outputs match the values in the truth table.</li>
</ul>
&nbsp;

<ol start="4">
<li><strong>All NOR Gate Implementation</strong></li>
</ol>
<strong>&nbsp;</strong>

<ol>
<li>Rewrite the function as the Product of Sums format</li>
</ol>
&nbsp;

<ol>
<li><strong>F = AB + BC’ = B(A+C’)</strong></li>
</ol>
&nbsp;

<ol>
<li>Draw the logic diagram using AND, OR and NOT gates:</li>
</ol>
&nbsp;

<ol>
<li>Convert the circuit diagram to <strong>all NOR gates implementation.</strong><strong>&nbsp;</strong></li>
</ol>
<ol>
<li>On Tinkercad, place a <strong>7402</strong> chip on the breadboard and build the circuit using the diagram (c). <strong><u>Note that 7402 chip has a different layout from 7400 chip.</u></strong></li>
</ol>
<ul>
<li>Connect the NOR gates according to the logic diagram.</li>
<li>Connect the inputs (A, B, C) to three switches, and the output F to a LED.</li>
<li>Press “Start Simulation”.</li>
<li>Apply all eight combinations of logic LOW and HIGH levels to the three gate inputs using the DIP switches. Observe if the circuit outputs match the values in the truth table.</li>
</ul>
&nbsp;

<ol start="5">
<li><strong>Homework</strong>: Draw the equivalent purely NAND/NOR gate representation of the function below and build the circuits on Tinkercad using NAND and NORchips, respectively. <strong><u>DO NOT simplify the function or change the fuction to sum-of-product or product-of-sum format! </u></strong>&nbsp;In the lab report, include the logic diagram with NAND implementation, the diagram with NOR implementation, the Tinkercad screenshot and link.</li>
</ol>
F = a(b + c) + bc’

<strong><u>Submission Instructions:</u></strong>

<u>Lab work submission</u>

<ol>
<li>Take screenshots of your circuits with eight input combinations.</li>
<li>Copy the link of your circuits for sharing.</li>
<li>On the Blackboard, click on Lab 5. Attach the screenshot from Step 1 and paste the link from Step 2 into the Comments area, then hit the Submit button.</li>
</ol>
&nbsp;

<u>Lab report submission</u>

<ol start="4">
<li>Lab report is needed for this lab. Please follow the guidelines and sample report on the Blackboard when you are writing your lab reports. Click on <strong>Lab 5 Report Submission</strong> to submit your report. It is due one week after the lab is done.</li>
</ol>
0 0 0 = 0

0 0 1 = 0

0 1 0 = 1

0 1 1 = 0

1 0 0 = 0

1 0 1 = 0

1 1 0 = 1

&nbsp;

1 1 1 = 1
