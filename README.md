# Sparta_CSharp_Bowling_game
Bowling game in c#

## rules:
- two players min
- 10 frames two balls eact frame
- strike = 10 points plus the point from the next two balls
- spare = 10 points plus points from the next ball
- Execptions to 10th frame:
- strike on last frame = gives the play 2 more balls adds all points together
- spare on last frame = give the player one more ball adds all points together

# Methods needed:

## player turns method:
- will need to change from player 1-2 
- will need to give each player 10 turns to bowl each turn has 2 rolls
- turns will can held in array make limt will be 10

## Bowling method:
- pick a random number 0-10 this happeneds twice, once for each ball
- if strike or number is ten then go to other pleyers turn
- 10th frame execeptions, if strike then get a two more rolls, is spare get one more roll

## Scoring method:
- score for player on will be held in array
- it will take the 1 ball and add to the second ball
-  for strikes 
