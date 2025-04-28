# eee472-cse422-assignment-03-solved
**TO GET THIS SOLUTION VISIT:** [EEE472/CSE422 Assignment-03 Solved](https://www.ankitcodinghub.com/product/eee472-cse422-artificial-intelligence-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;119744&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;EEE472\/CSE422 Assignment-03 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Lab Assignment-03

● Problem Statement

Here, are the following things you need to do using Alpha-Beta Pruning algorithm:

❖ Sample Input 1:

1. Enter your student id:

17301106

2. Minimum and Maximum value for the range of negative HP:

1 30

Note: Here, the second input is a space separated single line input string.

❖ Sample Input 1 Explanation:

Ex. 1 (17301106)

(Use 1st digit of your bracu student id) # Number of turns for the attacker agent

[Assume that both of them will get equal number of chances]

Ex. 60 (17301106)

(Use last 2 digits of your bracu student id in reverse) # Initial lifeline (HP) for the defender at initial state of the game

Ex. 3 (17301106)

(Use semester code-3rd digit of your bracu student id) # Number of bullets from which the final choice has to be made by the attacker.

Ex. 1 (1 30) # Minimum value for the range of negative HP values

Ex. 30 (1 30) # Maximum value for the range of negative HP values

❖ Sample Output 1:

1. Depth and Branches ratio is 2:3

2. Terminal States (leaf node values) are 19,22,9,2,26,16,16,27,16.

3. Left life(HP) of the defender after maximum damage caused by the attacker is 44

4. After Alpha-Beta Pruning Leaf Node Comparisons 7

1

❖ Sample Output 1 Explanation:

(Application of Alpha-Beta Pruning Algorithm)

MAX – Level 0 Attacker’s Turn / Initial Start MAX utility/Best Choice

MIN – Level 1 Defender’s Turn 3 branches

Leaf Nodes – Level 2 Terminal state 3^2=9 Leaf Nodes(Random States)

[19, 22, 9, 2, 26, 16, 16, 27, 16]

(Left lifeline/HP)

Left Life = (60 – 16) = 44

So, Left life(HP) of the defender after maximum damage caused by the attacker is 44 Hint:

1. Apply Alpha-Beta Pruning algorithm for sample output line 3 and line 4

2. Formula: Left life HP=Initial life HP-MAX negative HP

Note:

Terminal nodes are randomly generated values within the given range of negative HP (sample output line 2).

❖ Sample Input 2:

1. Enter your student id:

20201003

2. Minimum and Maximum value for the range of negative HP:

5 20

❖ Sample Output 2:

1. Depth and Branches ratio is 4:2

2. Terminal States(Leaf Nodes) are 18,13,5,12,10,5,13,7,17,8,6,8,5,11,13,18.

3. Left life(HP) of the defender after maximum damage caused by the attacker is 22

4. After Alpha-Beta Pruning Leaf Node Comparisons 13

2
