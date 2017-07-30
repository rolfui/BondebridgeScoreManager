# BondebridgeScoreManager
A HTML/Javascript program for managing "bondebride" scores.

## Installing

1. Download the file 'bondebridge.html' (You might also be able to open it directly in your browser.)
2. Open the file in your browser (Program is tested with MS Edge and Firefox, but compability issues might occur.)If those columns are removed, 
3. The program uses no network interaction after download. The HTML file can be used in your browser when offline as well.

## Usage

1. Add as many players as wanted by pressing the button "+ Add player +"
2. The leftmost column with text boxes is the players names. Type the players name here.
3. Play the game:
	1. Write what each player bids for that round in the bid row.
	2. Write what each player got for that round in the got row.
	3. The program will update the score row, and manages the scores.
	4. You can remove player with the "Remove Player" button. This is NOT undoable, so be careful.
	5. **Warning** The program assumes you use a deck of 52 cards. If more players than 4 are added, the program will remove rounds that you can't play with 52 cards.
		If those columns are removed, the information stored there is not recoverable.
	

### Some tips

* Type "enter" when writing in the "bid" or "got" row and the program will move the caret to the next appropriate text box to write in.

### Coding

If you want to add some code yourself, you are very welcome, but i must apologise for the "messy" code.
The program does probably not follow any good principles in eighter the javascript or HTML code.