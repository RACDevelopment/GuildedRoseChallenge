# Gilded Rose Refactoring Challenge

When run, Program.cs initialises a list of items in a shop.
Each time a key is pressed it updates the items for another day based on the features below.
The code works great but we think it could be improved. That is where you come in.

# Your challenge
**Primary goal**
Using clean coding principles refactor the code into something much better without breaking the features below.
We encorage you to make new classes, methods or even add tests to cover the features if you like.
The main focus of your attention should be on the Shop.cs and the `UpdateQuality()` method.

Once you have refactored the code you can add this new feature if you like
- "Conjured" items degrade in Quality twice as fast as normal items
     

```
Items have the following values:
	string Name
	int SellIn 
	int Quality
```

Implemented Features:
- Once the sell by date has passed, Quality degrades twice as fast								
- The Quality of an item is never negative														
- "Aged Brie" actually increases in Quality the older it gets									
- The Quality of an item is never more than 50													
- "Sulfuras", being a legendary item, never has to be sold or decreases in Quality				
- "Backstage passes", like aged brie, increases in Quality as it's SellIn value approaches;		
	- Quality increases by 2 when there are 10 days or less										
	- Quality increases by 3 when there are 5 days or less										
	- Quality drops to 0 after the concert

# Follow up questions
In addition to completing the task above, you will need to provide a short answer to the following questions:
- Describe the approach you took to refactor the Gilded Rose project
- Briefly describe what the term "clean code" means to you
- Which of the five SOLID principles do you think is the most important and why?

# Submitting your project
Upon completion, please create an archive of your project (i.e. zip, 7z, rar), upload it to Google Drive (or similar), and generate a public download link. 
Send the link, along with your answers to the follow up questions, to thomas.martin@royalautomobileclub.co.uk with the subject "CODING ASSIGNMENT - (Your name here)".
