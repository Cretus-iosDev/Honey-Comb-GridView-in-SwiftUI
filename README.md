# Honey-Comb-GridView-in-SwiftUI

i'm going to show how to create Honey Comb Grid View / ScrollView Using SwiftUI 

STEP - 1 :-
HOW TO ACHIVE THE HEXAGON SHAPE ?
As we all know that hexagon has 6 side . so, create 6 points which start moving frm pt6. all the way around to 1.

STEP - 2:-
HOW TO GEBERATE HONEY COMB ROWS FOR SCROLL_VIEW ?
1. create row 1 contain 2 columns
2. create row 2 contain 3 columns
3. create row 3 contains 2 columns and then continue the same pattern and generate the ROWS


STEP - 3:-
BASIC LOGIC?
1. if the rows comtains only one column(view) then moving the view left side with offset y = width of hexagon / 2
2. if previous rows and current  rows contains same amount of column then also repeating the smae process of moving view left
3.  by doing this we can achieve perfect honey comb structure



sample image of the output ;-

![Screenshot 2021-07-02 at 9 41 06 AM](https://user-images.githubusercontent.com/84556881/124219281-aabb5080-db19-11eb-9982-9f03cdf4e99e.png)




