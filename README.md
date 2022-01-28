# Introduction:
This is a school project using html, css, dom, js to create a Website Pokemon Hunting Game.

# Website Address:
It has already been uploaded to my school website:  
https://i6.cims.nyu.edu/~st3890/webdev/macro_assignment_03.html  
In each game, when you still have Pokeballs, you could click the button `play again` to continue play.  
When you have no Pokeballs, you can refresh the website to restart a game. 

# Rules for this game:
1. The user starts with 5 Pokeballs and 0 Pokemon.  
2. The user is presented with three grassy patches. Behind one of the cups is hidden a random Pokemon, behind another is hidden 2 additional Pokeballs, and behind the third is nothing.  
3. The user is asked to select one of three grassy patches by clicking their mouse on the desired patch. Every time they click on a patch the user will use 1 of their Pokeballs.  
4. If they find a Pokemon the number of caught Pokemon increases. If they find the 2 Pokeballs their number of Pokeballs increases by 2. If they do not find anything then nothing happens.  
5. In all cases the data displays are updated to reflect the user's current inventory (# of Pokeballs and # of Pokemon caught). 
6. The user can then click a "Play Again" button to try another round in which the Pokemon and Pokeballs will be randomly moved to a different patch. At the end of the round all of the grassy patches should be "locked" and un-clickable (i.e. the user should be prevented from selecting two different grassy patches during the same round) - hint: perhaps you need a global variable to keep track of the "state" of your game?  
7. The user can continue to play as long as they have Pokeballs left. If the user runs out of Pokeballs your program should not allow them to select another grassy patch. Display some kind of "game over" message when this happens. Hint: test your program with a lower initial Pokeball amount to make sure this feature works correctly!  


