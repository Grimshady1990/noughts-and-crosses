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
