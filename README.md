# Chess-Client-Server-Releases
This respository will be used to store my current side-project I've been working on. It includes a client and server GUI to play networked chess over the internet between 2 people. I'm creating it in my spare time and ~90% from scratch so there will be some bugs or features that aren't present. I mainly test this out with my father while running the server at my location (games are played from California to Maine).

There isn't any singeplayer yet, but I hope to one day have a solid enough understanding of how to create an AI/agent that could utilize machine learning to play at a comparable level to a basic individual. 

The Menu GUI was created using JavaFX for both the Server and Client, while the actual game GUI itself was created from scratch (minus the pieces). This was to allow me to get familiar with creating GUIs using Java. 

Due to an oversight on my part, it unfortuantely requires JDK 19 to run. I didn't realize that I should've used an earlier JDK such as 11 for compatibility until it was too late.

To play the game, run the server after installing JDK 19. Then, enter in a usable IP that your current machine is using, and click "Start". Some information will be passed to the GUI about the current state of the server. If you're using a private IP address, you'll need to use Port Forwarding on your router to connect over the internet.

Once the server is up, simply run the Chess Client, and navigate to the "Multiplayer" menu. From there, enter the Chess Server's IP address and Port that it's using, and hit "Connect". The client will open up the game in a new window. A chat box is availible to message your opponent during the game. To exit the game, click on the main Client window, hit "disconnect" and then click the "X" to close the window.

I hope to remake this onto a website at some point and utilize something like MySQL to handle account logins in the future, but for now this will remain a desktop application. 
