# numberGuesser
## code
* **main()** function will run the game, it will create a string variable with the length of 20, and then we will do a scan method to collect the users name and store it into that string varaible. after that we will print "Hello, (name)"
	after that we will write the guesser game program that will create a integer variable which will be a random integer, and then a variable that the player guess will go into, and a variable of the number of max guesses.
	then we will create a while loop with the parameter *keepGoing* , which is intitialized before the while loop. Then we will run the code asking for the user input and then will cehck if the user input == random integer var, if true then *keepGoing* if false then the system will print "wrong answer try again" if number of guesses >= 0. If number of guesses is <= 0, then the game will say that the player has lost, and *keepGoing* is turned to false
