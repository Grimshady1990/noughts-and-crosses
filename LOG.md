# Sept 3rd 21:12

Initial log: I have just added all the files that will be needed to start this project.

The goal of this project is going to be organization. This means committing regularly, using branches correctly and leaving meaningful comments.

This log will also double up as planning document, This means I will be tracking my thought process before and after writing the code so all thoughts regarding this project can be found here in chronological order.

With that said lets jump into the meat of it.

# Sept 3rd 21:21

File structure is now complete, I have also ran tests to make sure everything is linked successfully.

Now I need to think about how I am going to start building this project. It is a 2d board that will use JS for its functionality so I need to create a console version of the game that will be easily translated to the Dom when we move it to the window.

The goal of this project is to use factory functions that encapsulate specific functionality the 3 main functions are as follows:

- Gameboard: This function will manage everything to do with the gameboard.

- Game Controller: This function will manage the flow of the game. 

- Screen Controller: This function will manage everything we see on screen.

I must be very strict with these functions the gameboard must only contain elements that create the game board such as the arrays that make up the board and the values of the markers.

The game controller must only contain elements that manipulate the game board and direct the games conditions, for example: place markers in specific spaces, manage player values such as names and scores, and decide whether a move leads to a win, lose or illegal move.

The screen controller must only contain elements related to the DOM if everything inside the other two functions are working correctly then it should be very easy to translate that to the DOM without having to create any extra functionality

The first objective to achieve this goal is to write pseudo code for the gameboard and the game controller till we are fully satisfied that everything is where it needs to be. The problem is I am not to sure how to write pseudo code effectively which means the next goal for this project is to watch some youtube videos about pseudo code.

# Sept 3rd 22:03

TEST: This is a test log sent from my mobile device to see if i can successfully save to the branch and reclaim it from my PC.

# Sept 5th 23:46

I spent my evening learning about problem solving and pseudo code. And the main takeaway I got was that I dont have to solve all the problems right away. It is better to have something built that isn't great and work on the hard problems from there. Because it is easier to solve a problem from a position where you have gained experience in the situation instead of trying to figure out complex situation when you haven't even looked at any code.

Tomorrow I am going to fully digest the problem solving lesson in TOP so I have a more rounded idea. 

# Sept 14th 20:19

Okay so I still hadn't gone through the lessons on TOP as I have been on holiday. I feel a little ashamed that I haven't picked this up for this long, but I felt it was important to spend some quality time with my family.

Excuses out of the way I will now get on with the TOP problem solving class.

NOTE: I also want to add that I had absolutely no idea what I was going to be doing when I opened this project this log brought clear clarity to where i am at and i now see the true power off keeping this log.

# Sept 14 22:55

Ive gone back through the lesson and the refresher was useful. When I come back to the project I will first plan, then write the pseudocode and finally divide and conquer. Also I found a website called coderbyte that has daily coding challenges ive saved the bookmark under coding challenges.

# Sept 15th 20:32

Today I just received the book Think Like A Programmer by V. Anton Spraul Ive been told this book is essential reading. So my focus will be set on digesting as much of this book as can. 

I will use this log to recap what I learnt each day.

# Sept 15th 22:42

The start of the book is showcases little puzzles such as sliding grids and sudoku and gives you different ways of thinking about the problem. So far a interesting book.

