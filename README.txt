Problem Description
  Create a program, which, given an integer array of a valid sequence of throws for one game of American Ten-Pin Bowling, produces the total score for the game. Your code will become the core of a bowling score management system, so make sure it’s production-quality, i.e., adhering to the Google standards discussed this semester.
  Your input should be a string like the examples below.  You do not need to read your input from standard input or build a GUI.  The input string can be supplied directly to the invoking method.


The Rules
To briefly summarize the scoring for this form of bowling:
  ●One game of bowling is made up of ten frames.
  ●In each frame, the bowler has two throws to knock down all the pins.
  ●Possible results for a frame:
    oStrike (‘X’): the bowler knocks down all 10 pins on the first throw.
    The frame is over early. The score for the frame is 10 plus the total pins knocked down on the next two throws.
    oSpare (‘/’): the bowler knocks down all 10 pins using two throws.
    The score for the frame is 10 plus the number of pins knocked down on the next throw.
    oOpen frame: the bowler knocks down less than 10 pins with his two throws. The score for the frame is the total number of pins knocked down.
  ●The game score is the total of all frame scores. 
  ●Special rules for the 10th frame:
    oA strike in the tenth frame gives the bowler two bonus throws, to fill out the scoring formula for the last frame.
    oA spare in the tenth frame gives the bowler one bonus throw, to fill out the scoring formula for the last frame.
    oThese throws count as part of the 10th frame.
    oThe process does not repeat – for example, knocking down all 10 pins on a bonus throw does not provide any additional bonus throws.
