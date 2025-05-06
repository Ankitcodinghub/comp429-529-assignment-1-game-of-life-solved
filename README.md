# comp429-529-assignment-1-game-of-life-solved
**TO GET THIS SOLUTION VISIT:** [COMP429-529 Assignment 1-Game of Life Solved](https://www.ankitcodinghub.com/product/comp429-529-assignment-1-game-of-life-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;96019&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP429-529 Assignment 1-Game of Life Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
1 2 3 4 5 6 7 8 9

10

</div>
<div class="column">
f o r

</div>
<div class="column">
t in 0:T-1 //time step loop

forall (i,j) in 1:N x 1:N //simulation domain

<pre>     nNeigh = number of live neighbors of World(t)[i,j]
     World(t+1)[i,j] = DEAD
</pre>
if World(t)[i,j] AND (nNeigh == 2 or nNeigh ==3) then World(t+1)[i,j] = LIVE

else

World(t+1)[i,j] = (nNeigh == 3) end if

end forall

</div>
</div>
<div class="layoutArea">
<div class="column">
Notes: You may discuss the problems with your peers but the submitted work must be your own work. Late assignment will be accepted with a penalty of -20 points per day. Please submit your source code through blackboard. This assignment is worth 20% of your total grade (Part-I 8%, Part-II 12%). Part II will be released within a week and you will have an extra time for it. This is an individual assignment – no partners.

Part I: Game of Life

In this assignment you will implement a parallel version of the Game of Life in OpenMP. The universe of the Game of Life is a cellular automaton, in which cells live on a 2-dimensional world. They are born, live and die over successive generations. The world is defined as a binary-valued array, and each generation evolves according to the following rules:

<ul>
<li>Each cell can be one of two possible states: alive or dead.</li>
<li>Every cell interacts with its eight neighbours, which are the cells that are horizontally,
vertically and diagonally adjacent.
</li>
<li>At each step in time, the following transitions occur:
– Any live cell with fewer than two live neighbours dies, as if caused by under-population. – Any live cell with two or three live neighbours lives on to the next generation.

– Any live cell with more than three live neighbours dies, as if by overcrowding.

– Any dead cell with exactly three live neighbours becomes a live cell, as if by repro- duction.

The first generation can be created randomly and the successive generations will follow the above rules simultaneously to every cell. Each generation is a pure function of the preceding one. The rules continue to be applied repeatedly to create further generations. Here is the pseudocode for the Game of Life:
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Serial Code COMP 429/529- Parallel Programming ( Spring 2020): AssignmenPtA1R-TPaI:rtG1AME OF LIFE 11 end for

Serial Code

We are providing you with a working serial program that implements the Game of Life. The provided code creates a random world, distributing cells uniformly according to a specified probability. It then runs the game of life for a given number of generations, sending each generation to the gnuplot plotting program.

<ol>
<li>1 &nbsp;The program may be run from the command prompt as follows:</li>
<li>2 &nbsp;./life [-n &lt;int&gt;] [-i &lt;int&gt;] [-s &lt;int&gt;] [-p &lt;float &gt;] [-t &lt;int&gt;] [-d] [-step] [-g &lt;int&gt;]</li>
</ol>
3

4 With the arguments interpreted as follows:

</div>
</div>
<div class="layoutArea">
<div class="column">
<ol start="5">
<li>5 &nbsp;-n</li>
<li>6 &nbsp;-i</li>
<li>7 &nbsp;-s</li>
<li>8 &nbsp;-p</li>
<li>9 &nbsp;-t</li>
</ol>
</div>
<div class="column">
<pre>&lt;integer&gt; Number of mesh points in one dimension
&lt;integer&gt; Number of generations (or iterations)
</pre>
&lt;integer&gt; Random seed

&lt; f l o a t &gt; Distribution probability &lt;integer&gt; Number of threads

</div>
</div>
<div class="layoutArea">
<div class="column">
<ol start="10">
<li>10 &nbsp;-d</li>
<li>11 &nbsp;-g</li>
<li>12 &nbsp;-step pauses every iteration ( f o r debugging)</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>disables display
&lt;integer&gt; selects a game type
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
Requirements

</div>
</div>
<div class="layoutArea">
<div class="column">
• •

1 2 3 4 5 6

•

</div>
<div class="column">
To run the program, you will need the gnuplot plotting program to be installed on your computer. You can download the software from http://www.gnuplot.info .

The Makefile that we have provided includes an “arch” file that defines appropriate command line flags for the compiler.

<pre>To compile, type
      make
</pre>
<pre>To clean the objects and executables
      make clean
</pre>
<pre>Example run:
       ./life -n 500 -i 200 -p 0.2
</pre>
Since this program requires an interactive interface, you won’t be able to use the cam- pus clusters for plotting. Please develop and test your implementations on your local machines or on the computer labs on campus.

</div>
</div>
<div class="layoutArea">
<div class="column">
Task Parallelism

In this part of the assignment, you will employ multithreading to handle graphical display. You will modify the life simulator to run with two threads. One thread (the plotter thread)

</div>
</div>
<div class="layoutArea">
<div class="column">
Student Name: Page 2 of 7

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Data ParallelismCOMP 429/529- Parallel Programming ( Spring 2020): AssignmenPtA1R-TPaI:rtG1AME OF LIFE

</div>
</div>
<div class="layoutArea">
<div class="column">
should handle the display (via gnu plot) while the other thread should perform the cell updates. The two activities may take place concurrently. To synchronise the execution of the threads, barriers can be used. Data should be shared between the threads via shared- memory and the mesh plot must appear for each iteration.

Data Parallelism

In this part of the assignment, you will introduce additional threads to share the computa- tional workload in the cell update. To implement data parallelism, use a one-dimensional decomposition where the computational domain is to be divided (approximately) equally among all workers involved in the computation. Lastly, have the master thread initialize the game board. Although this approach isn’t scalable because of the first touch policy, the impact on this assignment won’t be noticed. Having the master initialise the game board ensures reproducible results and is extremely helpful for debugging.

You can introduce data or task parallelism in any order you like but the final implementation should use a single thread for plotting and the remaining threads to perform cell updates concurrently with the plotter thread. Starting with data parallel implementation might be easier.

Testing Correctness

<ul>
<li>You’ll notice that the serial program we provided allows you to input a random seed via the -s parameter. If you don’t specify this parameter, you obtain a seed based on the time of day. The program outputs this seed so that you will be able to reproduce a given run. In order to establish correctness, run your program on differing numbers of threads, including a single thread.</li>
<li>Another approach is to run with a problem that has a known solution. The literature is full of problems with known solutions. The simplest problems to test have the static patterns that do not change. We have provided one, which is called block still. You can find some examples on the Wikipedia page for Conway’s Game of Life Others include “blinkers” and gliders. A command line option -g can be used to select a game number. You can add the glider (spaceship) game if you like.</li>
<li>Another command line option -step has been added to allow you to “single step” through the game, one iteration at a time. This is handy for watching moving patterns.</li>
<li>Finally, another simple way of checking your results against the single thread implemen- tation is to output the contents of all game board locations in a systematic order (say, row major order), printing a single digit (1 or 0) for each position. You can then use the diff program to compare results. Of course, this assumes that your single processor implementation is correct!</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
Student Name: Page 3 of 7

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
Experiments COMP 429/529- Parallel Programming ( Spring 2020): AssignmenPtA1R-TPaI:rtG1AME OF LIFE Experiments

You are going to conduct an experimental performance study on KUACC. The aim of this experimental study is to get performance data across different numbers of threads and under different input sizes. In these experiments, you will disable plotting feature. You should still spare a thread for handling the display but this thread will not perform plotting.

• The first experiment will be a strong scaling study such that you will run your paral- lelized code multiple times under different thread counts. Please use the command line arguments below for this study.

1 bash$ ./life -n 2000 -i 500 -p 0.2 -d -t &lt;num-of-threads&gt;

&lt;num-of-threads&gt;will be 1, 2, 4, 8, 16, and 32. Plot the speedup and execution time

figures as a function of thread count and include them in your report.

• In the second experiment, you will evaluate your code’s performance under different input sizes, but with fixed thread count. The command that you will run is as follow.

1 bash$ ./life -n &lt;input-sizes&gt; -i 500 -p 0.2 -d -t 16

&lt;input-sizes&gt;that you will test are 2000, 4000, 6000, 8000, and 10000. Plot the execu- tion time as a function of input size. To observe the scaling, also include a plot which shows the execution time per data point (runningtime/n2), where n is the input size. Include your figures in the report.

To ensure that all of your performance data is taken from the same machine, you can run your commands for the first experiment and the second experiment in the same job script. In other words, all commands for both experiments will be submitted as a single job.

More details on how to run your code in KUACC cluster can be found in Section Environment below.

Submission

<ul>
<li>Document your work in a well-written report which discusses your findings.</li>
<li>Your report should present a clear evaluation of the design of your code, including
bottlenecks of the implementation, and describe any special coding or tuned parameters.
</li>
<li>We have provided a timer to allow you to measure the running time of your code. Observe the running time with and without the mesh plotter is on. You will see how much time is spent doing I/O.</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
Student Name: Page 4 of 7

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
Environment COMP 429/529- Parallel Programming ( Spring 2020): AssignmenPtA1R-TPaI:rtG1AME OF LIFE

<ul>
<li>Submit both the report and source code electronically through blackboard.</li>
<li>You only need to submit the final implementations for OpenMP if your task+data parallelism works properly.</li>
<li>Please create a parent folder named after your username(s). Your parent parent folder should include a report in pdf and a subdirectory for source code. Include all the necessary files to compile your code. Be sure to delete all object and executable files before creating a zip file.</li>
<li>GOOD LUCK. Environment
Even if you develop and test your implementations on your local machine or on the computer labs on campus, you must collect performance data on the KUACC cluster.
</li>
</ul>
<ul>
<li>Accessing KUACC outside of campus requires VPN. You can install VPN through this link: https://my.ku.edu.tr/faydali-linkler/</li>
<li>A detailed explanation is provided in http://login.kuacc.ku.edu.tr/ to run programs in the KUACC cluster. In this document, we briefly explain it for the Unix-based systems. For other platforms you can refer to the above link.</li>
<li>In order to log in to the KUACC cluster, you can use ssh (Secure Shell) in a command line as follows: The user name and passwords are the same as your email account.</li>
</ul>
<ol>
<li>1 &nbsp;bash$ ssh $&lt;$username$&gt;$@login.kuacc.ku.edu.tr</li>
<li>2 &nbsp;bash$ ssh dunat@login.kuacc.ku.edu.tr //example</li>
</ol>
<ul>
<li>The machine you logged into is called login node or front-end node. You are not supposed to run jobs in the login node but only compile them at the login node. The jobs run on the compute nodes by submitting job scripts.</li>
<li>To run jobs in the cluster, you have to change your directory to your scratch folder and work from there. The path to your scratch folder is</li>
</ul>
1 bash$ cd /scratch/users/username/

• To submit a job to the cluster, you can create and run a shell script with the following command:

1 bash$ sbatch &lt;scriptname&gt;.sh

</div>
</div>
<div class="layoutArea">
<div class="column">
Student Name: Page 5 of 7

</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
Grading COMP 429/529- Parallel Programming ( Spring 2020): AssignmenPtA1R-TPaI:rtG1AME OF LIFE • To check the status of your currently running job, you can run the following command:

1 bash$ squeue -u &lt;your-user-name&gt;

A sample of the shell script is provided in Blackboard along with the assignment folder. In the website of the KUACC cluster, a lot more details are provided.

• To copy any file from your local machine to the cluster, you can use the scp (secure copy) command on your local machine as follows:

<ol>
<li>1 &nbsp;scp -r &lt;filename&gt; &lt;username&gt;@login.kuacc.ku.edu.tr:/kuacc/users/&lt;username&gt;/</li>
<li>2 &nbsp;scp -r src_folder dunat@login.kuacc.ku.edu.tr:/kuacc/users/dunat/ //example
-r stands for recursive, so it will copy the src folder with its subfolders.
</li>
</ol>
• Likewise, in order to copy files from the cluster into the current directory in your local machine, you can use the following command on your local machine:

<ol>
<li>1 &nbsp;scp -r &lt;username&gt;@login.kuacc.ku.edu.tr:/kuacc/users/&lt;username&gt;/fileToBeCopied ./</li>
<li>2 &nbsp;scp -r dunat@login.kuacc.ku.edu.tr:/kuacc/users/dunat/src_code ./ //example</li>
</ol>
• To compile the assignment on the cluster, you can use the GNU or Intel compiler. The compilation commands and flags for the compilers are provided in a Makefile in the assignment folder. Before using the compilers, you firstly need to load their module if they are not already loaded as follows:

<ol>
<li>1 &nbsp;bash$ module avail //shows all available modules in KUACC</li>
<li>2 &nbsp;bash$ module list //list currently loaded modules.</li>
<li>3 &nbsp;bash$ module load intel/ipsxe2019-u1ce //loads Intel compiler</li>
<li>4 &nbsp;bash$ module load gcc/7.2.1/gcc //loads GNU compiler</li>
</ol>
<ul>
<li>If you have problems compiling or running jobs on KUACC, first check the website provided by the KU IT. If you cannot find the solution there, you can always post a question on Blackboard.</li>
<li>Don’t leave the experiments on KUACC to the last minutes of the deadline as the machine gets busy time to time. Note that there are many other people on campus using the cluster.</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 7">
<div class="layoutArea">
<div class="column">
&nbsp;

</div>
</div>
</div>
