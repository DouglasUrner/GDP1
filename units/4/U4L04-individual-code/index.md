
[//]: # (<p><iframe src="https://douglasurner.github.io/GDP1/units/4/U4L04-individual-code/" width="100%" height="666px"></iframe></p>)

## FP 4: Individual Code

### As A Team

If you have not already done so, decide on who will be responsible for each of the units of code that you identified when you did the project breakdown. Make sure this is reflected in your group's work breakdown document.

### Individually

Your code should be a function that can be called from the draw loop or from one of the major draw loop functions. Begin by planning it out in your notes:

* What does it do?
* What functions (abstractions) do you need?
* How can you test it to confirm that it works?

Then, write and test your code.

#### Tips & Suggestions

Each of the titles is a link to a minimal example in Game Lab, right click on the tip title to open the link in a new tab.

* **[Game Control / State Machine Pattern](https://studio.code.org/projects/gamelab/VwtePC2g_haoBfb7Z2D91MBKNE9xDeseLD_nDwvpCIA)**  
Create a state machine in the  ``draw()`` function to manage flow of the game. Call a function that handles each part of the game. Coding responsibility can be divided up by assigning the "top level" functions to members of the team.

* **[Scoring]()**  
There are two logical "hunks" of the scoring process:

1. Awarding or subtracting points, and
1. Displaying the score

Each hunk should be a function.

In Game Lab displaying text can be tricky because the text has to be displayed after any overlapping sprites or shapes are drawn. Otherwise the score will be hidden behind them. Be sure to call your function to display the score after you call ``drawSprites().``

## Submission

Get a link to your project by clicking on the Share button in Game Lab and then submit the link.
