6/12/2025

Since 3CG initial submission, I made many changes to UI that improve player experience, and I believe it is now a much more approachable and polished game than it was before.

Programming patterns are the same as 3CG, I did no major refactoring that incorporated new ones: 
Prototyping for my implementation of cards through CardClass and well as LocationClass,
States for storing a card's grab state as well as its position within the context of the 3CG gameplay loop,
Game Loop, as is implicit by the way Love2D handles its load, update, and draw functions; furthermore, my turnManager script uses a cycle of functions that call one another pseudo-recursively, only waiting for user input, to loop and progress turns,
Observers, with my use of reactive code within my turnManage, in terms of its response to changes in card state such as being shown or revealed in a location,
Components, especially with my compartamentalized location, deck, and player files that exclusively handled their own tasks and hardly relied on other scripts.

I got feedback from Phineas Asmelash over discord and a from a visiting friend Diego Brown.

All of the sprites and the game's background were made by myself with some help from Diego using the online tool, Piskel.

Here is a list of changes from my original submission:
While I did end up using a change in color or animations to communiate changing stats, I did use banners and a longer turn duration to better clue the player in on what was happening and when. 
Raising the current card in play also helped to indicate the actions of individual cards.
I added color coding to card stats to help distinguish them and relate them to the corresponding player stats.
Of course, I drew small images for each card to make them more recognizable and relate better to the mythological characters they portray. 
Since these pictures took up lots of card space, I opted for a pop-up box that reveals a card's powers rather than having them shown at all times.
Accompanying this, cards now darken when the player's cursor hovers over them.
The final issue I wanted to clean up were some timing bugs I began to notice with my original 3CG submission where cards would sporadically be revealed instantly, giving the player no time to react to it being revealed.
Each card now takes lots of time to be revealed, giving the player ample time to understand its effects on surrounding cards.

Overall this project was a blast, and I enjoyed far more than my revision of Solitaire.
Unlike with Solitaire, for which my first submission was terrible, I came back to 3CG with a respectable code base waiting for me, which certainly helped.
Another benefit was with the Final Project Plan which I made soon after finishing my first submission that gave me a solid direction where I should begin to make improvements this time around.
While I still feel that I work better in groups on projects like these, this was a very beneficial experience for me to learn how to work alone.
When specific programming problems became a headache, I could shift to working on art or another feature as a break to avoid getting stuck instead of having these tasks delegated to others.
Working on UI elements and overall user experience isn't something I thought about much before this class; I was more focused on design and gameplay.
However, working on this assignment and seeing the impact small changes in the user experience could have forced me to revalue the importance of these small aspects of games. I even had to open up Balatro to see how others had built their own UI systems.
While I had many struggles earlier in this class and still consider myself to be a functional, creative programmer, I can definitely see the value in working alone. Reading my own code is difficult enough, and I can't imagine how difficult it would have been sending it to others without this class.
