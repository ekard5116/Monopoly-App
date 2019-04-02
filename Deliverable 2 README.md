# Monopoly-App: Deliverable 2
A change that will be implemented will be the removal of the comas at the start of every line 
of the rules. In addition, a pregame preference menu will be implemented with the options that include icon selection, 
number of players, and possibly the edition of bots. The bots will be an optional edition that I hope will be a success. 
On top of that, I will begin to set up the actual game screen in which the match will take place.  
I will also consider using a separate controller class that has exclusive control of the game screen while the match is in progress. 
This will hopefully avoid the clutter that would come with having one controller in sole control of all the view classed and methods 
that interact between the view and model classes. The model classes will have the info regarding the icons number of players, 
the two six-sided dice and, if successful, the bot algorithms. All of which will be accessible by the controller classes 
so that the games screen displays the correct number of players and die rolls etc. I will test each addition to the app as 
I go and have methods return a message if successful or unsuccessful. The remaining option would be a n error message sent 
by the compiler. Lastly, I will go through many scenarios when all additions are implemented to ensure the app does not crash.

