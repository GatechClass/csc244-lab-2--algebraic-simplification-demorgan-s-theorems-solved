# csc244-lab-2--algebraic-simplification-demorgan-s-theorems-solved
**TO GET THIS SOLUTION VISIT:** [CSC244 Lab 2- Algebraic Simplification, DeMorgan’s Theorems Solved](https://mantutor.com/product/digital-logic-csc-244l-laboratory-2-algebraic-simplification-demorgans-theorems-and-sum-of-product-and-product-of-sum-implementations-solved/)


---

**For Custom/Order Solutions:** **Email:** mantutorcodes@gmail.com  

*We deliver quick, professional, and affordable assignment help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;113640&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSC244 Lab 2- Algebraic Simplification, DeMorgan’s Theorems Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (2 votes)    </div>
    </div>
Algebraic Simplification, DeMorgan’s Theorems, and Sum-of-Product and Product-of-Sum Implementations

1 Objectives

We will:

1. simplify logic circuits using Boolean theorems;

2. investigate the relationship between minterms, Maxterms, sum-of-products (SOP) implementation, and product-of-sums (POS) implementation;

3. prove that SOP and POS circuits can be built using only NAND and NOR gates, respectively.

2 Pre Lab

To be completed before your lab meets (individually):

2.1 Read the entire lab procedure.

• 3.1.1, 3.1.2, 3.1.3

• 3.2.1, 3.2.2 (pre-lab column), 3.2.3, 3.2.4, 3.2.5, 3.2.6

• 3.3.1, 3.3.2, 3.3.3

2.3 When you reduce an expression, show your work (write the number of each theorem/axiom used, one per line).

3 Lab Procedure

3.1 Simplification using DeMorgan’s Theorems

3.1.1 Complete the “F(A,B,C) original by-hand” column of the truth table in Table 1 for the following function (remember the order of operations! parentheses → NOT → AND → OR):

F(A,B,C) = (A′ + B′ · C)′ · (A′ + B′ · C′)′ (1)

3.1.2 Draw a logic diagram for the function in Eq. 1 using AND, OR, and NOT gates (remember the order of operations!).

3.1.3 Create a SV file named “functionABC.sv” that contains one SV module named functionABC. Write structural SV using the built-in logic gate modules to describe the operation of the circuit you created. Label any logic wires required.

3.1.4 Compile the SV using Quartus Prime Lite. Assign switches SW[2:0] to the three inputs (SW[2] as MSB A, SW[0] as LSB C), and LEDR0 to monitor the output.

3.1.5 Load the circuit to your FPGA. Verify the operation of your SV module by checking every possible input combination and filling in the “F(A,B,C) original on DE10” column of Table 1. Check that the output matches the column you calculated by hand. If they do not match, double check both the SV and the original truth table and correct the output.

Table 1: Truth Table for F(A,B,C)

A B C F(A,B,C) original F(A,B,C) original F(A,B,C) canonical

by-hand on DE10 (or reduced) on DE10

0 0 0

0 0 1

0 1 0

0 1 1

1 0 0

1 0 1

1 1 0

1 1 1

3.1.7 Based on your results (in Table 1), write an equivalent expression for the circuit as the canonical sum-of-products:

3.1.9 Compile the SV using Quartus Prime Lite. Assign switches SW[2:0] to the three inputs (SW[2] as MSB A, SW[0] as LSB C), and LEDR0 to monitor the output.

3.1.10 Load the circuit to your FPGA. Verify the operation of your SV module by checking every possible input combination and filling in the “F(A,B,C) canonical (or reduced) on DE10” column of Table 1. Check that the output matches the other two columns. If they do not match debug your canonical sum-of-products expression or SV.

3.2 Boolean Simplification

3.2.1 Examine the circuit in Fig. 1 and write the Boolean expression for the output, F.

Figure 1: Circuit to Simplify: F(w,x,y,z)

3.2.2 Complete the “Original F theory-Pre Lab” column of the truth table for F in Table 2.

3.2.3 Create a SV file named “functionWXYZ.sv” that contains one SV module named functionWXYZ. Write structural SV using the built-in logic gate modules to describe the operation of the circuit you created. Label any logic wires required.

3.2.4 Simplify the expression you obtained above, using Boolean theorems. Your lab report should show each step of this simplification, and you should list the theorem (or axiom) used in each step. Draw a logic diagram for the simplified expression.

3.2.5 Create a SV file named “functionWXYZsimplified.sv” that contains one SV module named functionWXYZsimplified. Write structural SV using the built-in logic gate modules to describe the operation of the circuit you created. Label any logic wires required on your diagram.

3.2.7 Create a third SV file named “fWXYZtoplevel.sv” that contains one SV module named fWXYZtoplevel. Add all three SV files to the same Quartus project, where the project should also be named fWXYZtoplevel. Use structural SV and explicit port mapping to connect together functionWXYZ and functionWXYZsimplified to the inputs and outputs of your DE10-Lite board.

Table 2: Truth Table for various implementation of F(w,x,y,z)

w x y z Original F Original F Simplified F

theory-Pre Lab empirical empirical

on DE10 on DE10

0 0 0 0

0 0 0 1

0 0 1 0

0 0 1 1

0 1 0 0

0 1 0 1

0 1 1 0

0 1 1 1

1 0 0 0

1 0 0 1

1 0 1 0

1 0 1 1

1 1 0 0

1 1 0 1

1 1 1 0

1 1 1 1

3.2.8 Compile the SV using Quartus Prime Lite. Assign switches SW[3:0] to the four inputs (SW[3] as MSB W, SW[0] as LSB Z) in the fWXYZtoplevel as inputs to both functionWXYZ and functionWXYZsimplified modules. Connect LEDR1 to monitor the output of functionWXYZ and LEDR0 as the output of functionWXYZsimplified.

3.2.9 Verify the operation of your modules by checking every possible input combination. Record these values in the appropriate columns of Table 2. If the two outputs do not match, debug your Boolean algebra and/or SV modules.

3.3 SOP and POS Implementations

Consider the following function:

f(A,B,C) = Xm(0,1,5)

3.3.1 Write this function as a canonical sum-of-products and design the corresponding circuit. Fill out the “F(A,B,C) original by-hand” column of Table 3.

3.3.2 Express the function as a list of Maxterms (or shorthand using our Q notation), give the corresponding canonical product-of-sums, and design the corresponding circuit.

3.3.3 Use Boolean algebra to simplify both of the above expressions to determine the minimal sumof-products and the minimal product-of-sums representation for the above function. Draw the corresponding logic diagrams for the minimal SOP and POS, including first-level inverters.

Table 3: Truth Table for F(A,B,C)

A B C F(A,B,C) original F(A,B,C) NAND F(A,B,C) NOR

by-hand SOP circuit POS circuit

0 0 0

0 0 1

0 1 0

0 1 1

1 0 0

1 0 1

1 1 0

1 1 1

Laboratory 2 Signoff Sheet

Student Name (Print in Black Ink):

To be turned in (scan a copy) with your lab report (back sheet) to D2L.

2.4

3.1.6

3.1.12

3.2.10

3.3.3

Lab Completed: by signing this, I affirm on my honor that I am aware of the student disciplinary code and that I have successfully completed this laboratory assignment.
