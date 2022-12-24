# FlappyBird-OOP-Project
## HCMIU - Semester 1 2022-2023
### Team: We showed up!
![](https://img.shields.io/badge/java-17-blue)
![](https://img.shields.io/badge/game-FlappyBird-brightgreen)

**Members:**  
**Ta Thi Phuong Thao - ITDSIU20082 - ITDSIU20082@student.hcmiu.edu.vn**  
**Khuc Ngoc Hoang - ITDSIU20127 - ITDSIU20127@student.hcmiu.edu.vn**  

**Introduction:**
* *Motivation: We love to make a loop game which means we can minimize the number of different levels as the errors in each level like Boom Game, PacMan.
  As we know, Flappy Bird is a popular game title so we can find many references and assets. We want to build the new one that is interesting with the same rules game.*  


* *Task allocation:*
>1. Ta Thi Phuong Thao: write report, code framework, CloudControl, Coin, BirdEatCoin, init Pipe, find bird render, contribute to Pipe, PipeTest, find Sound, make PowerPoint slides.
>2. Khuc Ngoc Hoang: write report, find 2 bird renders, contribute to Bird, idea + code GameOver, code Score, make PowerPoint slides, init cloud, code Bird, code Bird Hit Pipe.


**Technologies:**
> Java 17  
> Java AWT (Abstract Window Toolkit)  
> JLayer

**Launch:**  
<sub> Instruction: in Intellij, click File > Project Structure > Modules > Add File jar (JLayer)</sub>
- Game entrance is `FlappyBird-OOP-Project\src\FlappyBird\Main.java` run `main method` directly.
- Use the Command Line java -jar FlappyBird-OOP-Project.jar to run game.

**The project "Flappy Bird":**
> 1. The rules:
- About the rules of the button and the arrow flashes
  > a) The button:
    + buttonOne (the red button): This is the button to select different birds in different levels. When you reach a certain milestone, you will unlock a bird with          a different look. In that time, this button will help you select the favorite bird if you want.
    + buttonTwo (the yellow button): When you press space on this button, you will start the game.
    + buttonThree (the blue button): This is the leaderboard to show the score you have achieved.

  > b) The signal to move (the arrow flashes):
    + "^" signal: to move up
    + "v" signal: to move down
    + ">" signal: to go the next button
    + "<" signal: to return the before button
- About the rules to play the game
    + Using the signals to move the birds by space (fly up)
    + During the play, the player must maintain a safe distance between the bird and the pipe. This means that the bird must not fly too high (hit the upper pipe)           nor should the bird fly too low (hit the lower pipe). If the bird follows the safe spots, the game will continue.
    + In the case, if the bird hits the pipe, it will die and the game will be over.
> 2. Design:
- Background: We changed the background instead of the simple blue background, it's now more attractive because of the beautiful scene (blue sky, mountain, jungle,       ground).
- Cloud: The clouds are shown throughout the game from start to finish (this is a new point in our game). The clouds will be moved dynamically.
- Welcome: The game name “Flappy bird” was added at the beginning. Moreover, we made it more colorful and beautiful. And the words "Press space to continue" are         displayed under the game name. We added them to liven up the welcome part.
- GameOver: You can input the name and if the score is in top 5, you can see in button 3. If the score is the new highest point, a text will appear. Try to get the highest to know what is the text.  
- Sound: sound is added to make player more interesting.  
> 3. Feature:  
- Which features are completed: presented above   
- Which features are incompleted: Lock the bird skin  
- Future features if you want to developer further after the course:
1. Added some new features such as adding other characters, other obstacles,...
2. Maybe play with AI
3. Make the graphic more eye-catching
* Discuss challenges in the project:  
1. Difficult to understand each member
2. Time management
3. Problem running the code
  (Framework, Multi-threading)
* Presentation: https://www.canva.com/design/DAFT_YlqJ-g/la5JWCm5shy2J_6RaOWKSQ/edit?utm_content=DAFT_YlqJ-g&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton

* UML Diagram:  
![284021886_352971583571647_7295832931427040568_n](https://user-images.githubusercontent.com/91868308/172973312-d459eb50-dbd3-4166-885c-517686ef9f7e.png)

* **Reference:**  
https://github.com/sunzhichao/FlappyBird
