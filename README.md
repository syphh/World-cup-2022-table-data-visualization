# World-cup-2022-table-data-visualization
We can agree that one of the excitement factors of a world cup knockout stage is how much the ranking table changes during the match, especially during the last day.
This is why we may want to visualize how much the table of each group changed during the last matches, to identify the most exciting group and the most boring one.

In this project, we start by extracting data about knockout stage matches, especially elements that can have an impact on the ranking (goals and cards).
Then we simulate the last day's matches by checking if the table changed at each important event of the match.
Finally, we create a nice visualization for each group to understand the evolution.

N.B.: Current rules used to sort teams of a same group are:

• Step 1:
(a) greatest number of points obtained in all group matches;
(b) superior goal difference in all group matches;
(c) greatest number of goals scored in all group matches.

• Step 2:
If two or more teams in the same group are equal on the basis of the above three criteria, their rankings will be determined as follows:
(d) greatest number of points obtained in the group matches between the teams concerned;
(e) superior goal difference resulting from the group matches between the teams concerned;
(f) greatest number of goals scored in all group matches between the teams concerned;
(g) highest team conduct score relating to the number of yellow and red cards obtained;
(h) drawing of lots by FIFA.

(source: https://www.fifa.com/fifaplus/en/articles/world-cup-qatar-2022-tiebreakers-group-stage-last-16-goal-difference-goals-scored-cards)
