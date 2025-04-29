# cs303-project-1--ai-algorithm-for-reversed-reversi-solved
**TO GET THIS SOLUTION VISIT:** [CS303 Project 1- AI Algorithm for Reversed Reversi Solved](https://www.ankitcodinghub.com/product/cs303-ai-algorithm-for-reversed-reversi-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;116316&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS303 Project 1- AI Algorithm for Reversed Reversi Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
1 Overall Description

In this assignment, we use the default board of size 8*8 board (administrators can modify the settings as needed). Students need to implement the AI algorithm of Reversed Reversi according to the interface requirements and submit it to the system as required for usability testing and round-robin.

The Project is divided into two phases, each with one or two weeks for coding or improving your current coding.

Reversed Reversi

After Phase 2, a carefully-written experiment report needs to be submitted.

Coding_Score =（Phase1+Phase2）/2

Project1_Score = Coding_Score *0.7+ Report_Score *0.3

2 The Use of the Platform

The Reversed Reversi platform http://172.18.34.89:8080/ is logged in with the student ID and password. The default password is the student ID. At the first login, the system will remind you to change the password. After logging in successfully, you can see the below interface.

Now, you can submit your own AI algorithm to the Reversed Reversi battle platform. The platform will first do usability test after submission. The submission is successful only if your AI algorithm passes the usability test. After submitting your AI algorithm successfully, you can click on “Auto Play” to challenge the player who ranks ahead of you for a PK. In order to avoid the first-hand advantage, the PK is played for 2 rounds with each other starting the game first. In each round, if one of your wins, then its score is increased by 5 points. If one of you loses, then its score is reduced by 5 points. If it is a draw, the scores remain unchanged.

The whole battle process will be recorded for each match. You can play back the game you just experienced by playing and backing buttons, or you can download the game data as a text file so that you can debug or review their code and algorithms. On the right side, you can see the leaderboards, showing only the top ten and their points, as well as your ranking and points. Click on “play” to see the live broadcast for the battle of the top-ten players. If you want to evaluate your newly uploaded algorithm, please use the function of “playto”. Just input the opponent you want to challenge and click “playto”, then you can play a pre-PK with this opponent. The pre-PK does not affect your rankings.

Your ranking on the platform does not affect your final score. The platform is just a tool to help you improve your algorithm.

After the Phase 2 DDL, the round-robin is started. Every student will play a PK with each other student. The score is accumulated, and each student’s ranking is given according to the final points.

3 Code Requirements

1、Python version: 3.7.6 2、Code template:

1 import numpy as np

2 import random

3 import time

4

5

COLOR_BLACK=-1

6 COLOR_WHITE=1

7 COLOR_NONE=0

8 random.seed(0)

9 #don’t change the class name

10 class AI(object):

11 #chessboard_size, color, time_out passed from agent

12 def __init__(self, chessboard_size, color, time_out):

13 self.chessboard_size = chessboard_size

14 #You are white or black

15 self.color = color

16 #the max time you should use, your algorithm’s run time must not exceed the time limit.

17 self.time_out = time_out

18 # You need to add your decision to your candidate_list. The system will get the end of your candidate_list as your decision.

19 self.candidate_list = []

20

21

22

# The input is the current chessboard. Chessboard is a numpy array.

23 def go(self, chessboard):

24 # Clear candidate_list, must do this step

25 self.candidate_list.clear()

26 #==================================================================

27 #Write your algorithm here

28 #Here is the simplest sample:Random decision

29 idx = np.where(chessboard == COLOR_NONE)

30 idx = list(zip(idx[0], idx[1]))

31 #==============Find new pos========================================

32 # Make sure that the position of your decision on the chess board is empty.

33 # If not, the system will return error.

34 # Add your decision into candidate_list, Records the chessboard

35 # You need to add all the positions which are valid

36 # candidate_list example: [(3,3),(4,4)]

37 # You need append your decision at the end of the candidate_list,

38 #candidate_list example: [(3,3),(4,4),(4,4)]

39 # we will pick the last element of the candidate_list as the position you choose.

40 #In above example, we will pick (4,4) as your decision.

41

42 # If there is no valid position, you must return an empty list.

1、 Time measurement start = time.time()

… algorithm…

run_time = (time.time() – start)

2、 Note：import os not allowed to use

3、 The use of memory cannot go beyond 100M, the time to find a place to drop cannot be longer than 5s, the whole battle cannot be longer than 180s

4 Requirements in Each Phase

4.1 Phase 1

Usability testing: In this test, we will use some simple board test cases where students need to find the best place to drop. Only jobs that pass the usability test can pass. This is to prevent students from submitting code including illegal operations, infinite loop or random drop. The usability testing includes: the os package cannot be imported in the code file to prevent the student code from destroying the operation of the system.

A total of 10 test cases were prepared, each with 10 points, and the scores were determined by the number of test cases passed.

4.2 Phase 2

Students who pass the usability test can use the platform to improve the algorithm. The specific competition rules of the platform are as follows: Students can submit their AI algorithm to the Reversed Reversi battle platform (it is a successful submission if it passes the usability test). After a successful submission, you can click on “Auto Play” to challenge the player who ranks ahead of you for a PK. In order to avoid the firsthand advantage, the PK is played for 2 rounds with each other starting the game first. In each round, if one of you wins, then its score is increased by 5 points. If one of you loses, then its score is reduced by 5 points. If it is a draw, the scores remain unchanged.

Students can submit and update their AI algorithm to the Reversed Reversi battle platform before Phase 2 DDL. After the Phase 2 DDL, the round-robin is started. Every student will play a PK with each other student. The score is accumulated and the ranking for each student is given according to the final points.
