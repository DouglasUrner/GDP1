
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

* **[Scoring](https://studio.code.org/projects/gamelab/9HMW0-xOHzGla5kDf1paIDAS008QL-_tW36Xb9SS0sc)**  
There are two logical "hunks" of the scoring process:

  * Awarding or subtracting points, and
  * Displaying the score

  Each hunk should be a function.

  In Game Lab displaying text can be tricky because the text has to be displayed after any overlapping sprites or shapes are drawn. Otherwise the score will be hidden behind them. Be sure to call your function to display the score after you call ``drawSprites().``
  
* **[Buttons](https://studio.code.org/projects/gamelab/nnwQFaeqqjdUCjZS5P0nqy2bRjNADl3NDnJ0ZznArdM)**  
Buttons are useful when you want, or need, to offer the player a way to do "non-play" actions during the game – for example to pause or quit or restart the game. They are especially useful in "endless" games.
  
* **[Abstraction: Using Functions To Hide Complexity](https://studio.code.org/projects/gamelab/DD-rPmAOT0Bf3USyMA5_wLODyZtK2eilz924np3qAHA)**  
When computer scientists use the term *abstraction* they are often referring to the practice of creating a function to hide details that make the code harder to understand.

## Submission

Get a link to your project by clicking on the Share button in Game Lab and then submit the link.