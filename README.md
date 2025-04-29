# cs211-assignment-1-stacks-using-array-solved
**TO GET THIS SOLUTION VISIT:** [CS211 Assignment 1-Stacks using array Solved](https://www.ankitcodinghub.com/product/cs-211-data-structures-and-algorithms-lab-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;116665&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS211 Assignment 1-Stacks using array Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Assignment no. 1

Objective To implement Stacks using array and use it to solve the Tower of

Hanoi/ Tower of Brahma/ Lucas’

Tower

Penalty for violating naming convention(s) 5%

There are two tasks in this assignment – Task 1 and Task 2. The solution for Task 1 must be used to solve Task 2 and the evaluation will be based on the output of Task 2.

Task 1

The objective of this task is to implement Stacks using arrays. You need to implement PUSH and POP operations. There should be checks for Stack Overflow and Stack Underflow. The maximum size of stacks must be n, which will be given as a command-line argument.

Task 2

The objective of this task is to solve the Tower of Hanoi/ Tower of Brahma/ Lucas’ Tower (ToH). In TOH, there are three poles A, B, and C. There are n disks each of them has a different diameter. Initially A contains all these n disks in the increasing order of diameter (the largest disk is at the bottom of the pole).

Objective: To move all the n disks to the pole C by following the below rules:

(i) only one disk can be moved at a time;

(ii) each move consists of taking the upper disk from one of the poles and placing it on top of another pole or on an empty pole;

(iii) a disk cannot be placed on top of a disk with less diameter.

While solving this problem, you have to use three stacks A, B, C in place of three poles and each move consists of popping one element from one stack and pushing that element to another stack. Initially all disks are to be pushed to the stack A.

Command-line argument:

Your program should receive one command-line argument: the number n of disks. You can assume that the kth disk has a diameter k units.

Output

The output of your program should be in a file named ‘toh.txt’. Each line should denote a stack operation. The first n lines must be “Push disk &lt;k&gt; to Stack A”, where k takes values n to 1 (in decreasing order). This is required to make sure that all n disks are in Stack A before solving the problem. Then the remaining stack operations must be written in order to achieve the goal,

i.e., to place all disks in Stack C in the same order in which they present in Stack A initially. If the stack operation is Push the disk 3 to Stack B, then the corresponding line must be “Push disk 3 to Stack B”. If the stack operation is Pop the disk 4 from Stack B, then the corresponding line must be “Pop disk 4 from Stack B”. In short, every line must have six words where each two adjacent words are separated by a single white space.

Word 1: “Push” or “Pop”

Word 2: “disk”

Word 3: &lt;the-disk-number&gt;

Word 4: “to” (if Word 1 is “Push”) or “from” (if Word 1 is “Pop”)

Word 5: “Stack”

Word 6: “A” or “B” or “C”

Submission

● The program you submit should output: toh.txt when we run the program for evaluation.

● Test well before submission. Some sample outputs are attached.

● Follow some coding style uniformly. Provide proper comments in your code.

Evaluation
