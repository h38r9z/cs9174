java c
MGTSC 212 Fall 2024 
Lab Assignment 4 
Due by 11:59 PM, 06 Dec. 2024 
Total points: 80Perform. all calculations using Excel,   when calculations are needed:   no other source of   answers    requiring   calculation   will   be   permitted. Some of   the answers will automatically appear in the   Answer   worksheet (except   tables   and   graphs). Leave the table(s)   and graph(s) within   the   respective   worksheet   unless   instructed to   copy-paste   them to   the   Answer   sheet.   After   calculating   answers   on   the   designated   worksheet   for   each   problem,   if   they   do   not   automatically   appear   in   the   Answer   sheet,   Copy   and   Paste   123   (Values)   to   the   Answer   sheet   without   rounding. Rounded numbers will be treated as errors.   Do   not   type   values   into   the   Answer   sheet   that   you   calculate   elsewhere.   Any   numbers   written   directly   without   excel   cell   reference   or   formula   into   the   answer   cells   will   get   0 unless otherwise specified   [e.g., you can type in the given x-values while calculatingY(̂)]. You can also type   degrees of   freedom   whenever   applicable   (as   there   is   no   rounding   involved).
[3 points] Put your student ID and name in the designated   shaded   cells   in the   Answer   sheet.
Questions: 
Use α   =   5% for all hypothesis testing-related questions.
1.         [7 points] In the Rand worksheet, you are given a   set of   two randomly   generated numbers between   0   and   1   in   cells A4 to A5. Treat these values   as   the   cumulative   probabilities   under   a   standard Normal   Distribution.   Now simulate values in cells B4 to B5 from   the   Standard   Normal   distribution   such   that   the   area   to   the   left   reflects   the values in cells A4 - A5. Copy the values   from B4   to   B5   as   Paste   Special   in   cells   C9   to   C10   of   the   Answer worksheet   [paste   as   values   123,   slide   #45   from   Lab-cycle1_data_summary]. Note that,   failure   to   fulfill   the   instructions for the Rand portion, as outlined above, will result in a   15% deduction from your earned marks for   Lab Assignment 4.
2.         [12 points] The VIF worksheet contains data   on   Income   tax   (Y)   and   other   related   explanatory   variables   with   an   estimated regression   model   for   the   Income   tax   based   on   a   list   of explanatory variables   as   appeared   in   the   regression   output. We   suspect   that   there   maybe   multicollinearity   in   the   system   and   we   would   like   to   find   the VIF   value   of   Operating   expenses.
a.          [8 pts.] Run the VIF regression and save it   either   in the   same worksheet   or   a   separate worksheet
b.         [4   pts.]   Calculate   the   VIF   value   in   the   VIF   worksheet   (cell   W19).   You   can   also   transfer   the   VIF   (calculated elsewhere) without rounding in cell W19.
3.         [33   points]   The Regs worksheet contains   summarized   regression   results   for the CO2 emissions (metric tons per capita) for five different models. Here   is   a   screenshot   of   the related   data   sample:
Bangladeshis the base country for the India and Malaysia dummy variables. MVAIND and MVAMYS are   the interaction variables between Manufacturing, value-added and country dummies.
Based   on the   regression results   answer the   following   questions   (also   included   in the   textbox   within   the   Regs   worksheet).
a.          [2 pts.] What is the value of   the Mean Square Error   in Model 3?
b.         [4 pts.] What代 写MGTSC 212 Fall 2024 Lab Assignment 4R
代做程序编程语言   is   the   value   of   the   test   statistic   totest   H0:   βMVA      =   βTime_Year      =       βOil   rents      =   βGDP   growth      =   0 vs.    Ha: at least one   βj      ≠   0   in Model 3? 
c.          [2 pts.] What is the sample standard deviation   of   CO2   emissions in Model 3?
d.         [2 pts.] What   is the   estimated   standard   error   of   the   error,   i.e., what   is the   value   ofσ(̂)?   [in   OLS regression,   we   assume   that   the   error, ε~N(0,    σ2)] in Model 3?
e.          [1.5 pts.] In Model 3, what   is   the   value   of   the test statistic to   test   that   βoil   rents is significantly different from zero?
f.          [0.5 pts.] What is the Residual   degrees   of   freedom in Model 3?
g.         [2 pts.] What   is   the p-value of   the   test   that   βoil   rents is significantly different from zero in Model 3?
h.         [2 pts.] What is the correlation between CO2 emissions (Y) and GDP growth (X) based on the sample data   utilized in these models?
i.          [3 pts.] In Model 1, what   will   be   the predicted   CO2   emissions   from   a   country with   a   5.5%   GDP   growth?
j.          [6      pts.]      Using Model       4 estimates,    what      will      be      the      predicted       CO2      emissions      in      Malaysia    with   Manufacturing, value added =   15.72%, Time_Year=1,   Oil rents =    0.5%, and   a   GDP   growth   of   6.18%?
k.         [1 pt.] In Model 3, what   is   the   value   of   β(̂)MVA?
l.          [1 pt.] In Model 3, what   is   the   value   of   the   standard   error   of   β(̂)MVA?
m.      [4 pts.] In Model 3, you want to test if   the predicted CO2 emissions is increased by less than 0.2 units due   to   a 1% increase in the Manufacturing, value added when the   other   variables   are   in the   model   and their   values are held constant. Calculate the related test statistic value.
n.         [2 pts.] In Model 3, calculate   the   p-value   totest   H0:    βMVA      ≥   0. 2 Vs.    Ha: βMVA      < 0. 2. 
4. [25 points] The LogReg worksheet   contains   data   on university   admission   for   a   sample   of 400   students   with   their   respective   GRE   and   GPA   scores.   A   researcher   is   interested   in   how   variables,   such   as   GRE   (Graduate   Record   Exam   scores)   and   GPA   (grade   point   average),   affect   admission   into   graduate   school.   The   response   variable, admit/do not admit, is a binary variable. Complete the necessary   calculations to   get   the   optimal   value
of   β(̂)0,      β(̂)1,      β(̂)2   in the logit function: β0    + β1GRE   + β2GPA.
a.          [8 pts.] Complete the column calculations for Logit,   e^Logit, Probability,   and   Log-likelihood.
b.         [3 pts.] Report the optimalβ(̂)0,       β(̂)1,       β(̂)2    values in cells K4 to K6
c.          [2 pts.] Report the maximized log-likelihood value in cell K7
d.         [3 pts.] What is the probability of   getting admission with a GRE   score of   750   and   a   GPA   of   4?
e.          [2 pts.] What is the Odds of   getting admission with   a   GRE   score   of   750   and   a   GPA   of   4?
f.          [3 pts.] What is the probability of   getting   admission with   a   GRE   score   of   750   and   a   GPA   of   3?
g.         [2 pts.] What is the Odds of   getting admission with a   GRE   score   of   750   and   a   GPA of   3?
h.         [2 pts.] What is the Odds ratio for getting admission with   a   fixed   GRE   score   due to   a   1-unit   increase   in the   GPA?





         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
