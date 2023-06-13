## CMPT 276 Project

# Find the Queen Bee <br>


## Instructions

### How to Play

To play the game you need the follow the instructions below. The controls of the game are as follows:

- 'W', 'A', 'S', 'D' as well as the arrow keys are used to move the player up, left, down and right respectively.
- 'Esc' can be used to pause the game to view the controls, or quit the game
- To see the objective of the game as well as other instructions, move the arrow using the keyboard to 'Controls ' on the Main Screen.

### How to Build

To build the game you must have the following installed:

- [Java](https://www.java.com/en/)
- [Maven](https://maven.apache.org/) 
- [Git](https://git-scm.com/) (Optional)

Download the repository and unzip or clone the repository using git:

`git clone https://csil-git1.cs.surrey.sfu.ca/cmpt276f22_group16/project.git`

Build the project running the following Maven command:

`mvn package`

This generates a jar file located in the `target` directory

### How to Run

After following [how to build](#how-to-build), you can run the game by running the following command:

`mvn exec:java` 

or 

`java -jar target/BeeMaze-1.jar`

Both commands run the game.

### How to Test

After following [how to build](#how-to-build), you can test the game by running
the following command:

`mvn test`

### Generate Javadocs

To generate Javadocs for the project, run the following command:

`mvn javadoc:javadoc`

The Javadocs are located in the `target/site/apidocs` directory and can be viewed
by opening the `index.html` file in your browser.
