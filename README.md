# CS230
Main Project for CS 230: Operating Platforms

The Gaming Room is a client who desired a web-based application for running a gam titled "Draw It or Lose It". This game would allow for one or more players to be assigned to one or more teams which participated in a game. Multiple games could be stored by the game service, although each game could only have one instance.
Game data is stored on a password-protected REST API.

The design documentation details the game requirements from the client, the Gaming Room, as well as details class/object architecture. It details decisions made in the design proccess and provides justification for each decision. It also explains the pros and cons of each potential operating system on both the server and the client side. While the decision of which operating system is used is up to the client, these details will provide some amount of collaboration between the developer and the client in making that decision. 

Writing the constraints and requirements in the design document provided clarity on exactly what details must be included in the game code. Additionally, if there are any discrepincies between what was requested by the client and what was understood by the developer, those would be brought to light and corrected after the design document was presented to the Gaming Room. 

In future revisions, I would provide more details on the Evaluation section. This is an area that I am still learning, and even between the time that I wrote the document and now, I have learned more about the differences between operating systems and could provide more details on each. Also, there is one un-filled-out section on page 3 titled "System Architecture View" to be filled out before the final revision is complete. 

In writing the program, it is critical to consider what the end user's need are. This can be done through input validation and considering ways to make the software more self-explanatory and easy to use. This can include memory and storage optimization (may make the program less laggy), error messages and input validation (corrects bad inputs), and providing adequate instructions available prior to and during gameplay. Anything that provides a smoother, more fun game experience will enhance the user experience. 

When designing the software, I used a REST API to store user and game data. Since this is a web application, it may be run on various operating systems, and using a REST API will provide elegant and secure connections between the end user and the game server. During the development of the program itself, polymorphism, encapsulation, abstraction, and inheritance are all used to prevent unnecessary data from being shared between classes, and to prevent unnecessary computing power and storage from bewing required while running the progam. 
