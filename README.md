# Project

#### Original Project Timeline:
| Deliverables      | Project Milestone                |
| ----------------- | -------------------------------- |
| Deliverable 1     | Review Javascript and HTML       |
| Deliverable 2     | Create landscape of game         |
| Deliverable 3     | Finish maze in game              |
| Deliverable 4     | Make enemies that attack player  |
| Deliverable 5     | Make game interactive for player |
| Final Project Due | Complete entire game             |


**Final Project Links**
- Link to Final Project Introduction Website Code: https://glitch.com/edit/#!/maze-game-cc2?path=index.html%3A1%3A0
- Link to Final Project Introduction Website: https://maze-game-cc2.glitch.me/
- Link to Final Project Maze Website Code: https://glitch.com/edit/#!/vr-maze?path=index.html%3A1%3A0
- Link to Final Project Maze Website: https://vr-maze.glitch.me/
- Link to Feedback Form: https://docs.google.com/forms/d/e/1FAIpQLScWS6XJToY0OSDGpIbjWBxG3KS6cGMndFiZEqzcNGASyTrFew/viewform?usp=sf_link




**Deliverable 5 -**
12 May, 2022

1. *What was your goal for this deliverable, as defined on your Learning Plan?*
2. My original goal for this deliverable was to make the player able to break and put down blocks, but then I changed it to be to make enemies in the game that chased the player.
3. *Did you meet this goal? If not, why?*
4. No, I still have not been able to add enemies into the game.
5. *What needs to happen for you to stay on schedule from this point forward (e.g., change of plan, putting in extra time, getting help, etc.)?*
6. To stay on schedule from now on, I think I need to start working outside of class and putting in extra time. However, I just don't know if I'm going to be able to code in the enemies at all. Now that the final project submission is coming up, I realized that there was still a lot of stuff I needed to do. None of them were very big changes, but they were just a lot of small additions to increase the quality of my project and to get it ready for the submission. I focused more on this than on adding enemies, which is why I wasn't able to get them done by this deliverable. If I put in extra time, I might be able to get them done by the time the project is due. Otherwise, I'll need to remove them from the plan.

So far what I've done on my project for this deliverable is that I've added a lot of smaller changes that improved the overall quality of the project, but not anything big. For example, even though I wasn't able to reach my goal for this deliverable, I added things like a three minute timer that the player has to finish the maze before that, which took a surprisingly long time for me to figure out. If the player hasn't reached the end of the maze before the three minutes are up, the page will reload, sending the player back to the start of the maze. I also improved the beginning and end of the maze. Before, you would just start in the middle of a hallway with empty space behind you that you could use to go around the maze instead of through it, and it ended with another hallway also ending in empty space. Now, I made it so the player starts in a small room, and the maze ends in another room with a marker in it to signify that they have reached the end. I also updated the instructions on the first page to make it more clear and to reflect all the recent changes and improvements. When I was done with that, I started working on adding enemies, and I spent a some time experimenting with how to do that. This is part of the javascript code for the timer:
```
const setTimerMinutes = 3;
let time = setTimerMinutes * 60;
```
This is all of the code for the timer in HTML:
```
<p id="countdown"></p>
```
Feedback: A plan for getting feedback that I could use is to add another button on the original website with the instructions that says something like "Give Feedback" that, when they click on it, it would take them to a Google Form with questions asking what could be improved and how they rated different aspects of it and what their thoughts were of it.




**Deliverable 4 -**
21 April, 2022

1. *What was your goal for this deliverable, as defined on your Learning Plan?*
2. My goal for this deliverable was to make enemies that followed around and attacked the player
3. *Did you meet this goal? If not, why?*
4. Unfortunately, I was not able to meet my goal of making the enemies
5. *What needs to happen for you to stay on schedule from this point forward (e.g., change of plan, putting in extra time, getting help, etc.)?*
6. To get on schedule, I need to put in extra time at home to code in the enemies. I underestimated how long it would take to finish other parts of the maze, so I thought that I would have enough time by this deliverable to have the enemies already coded in. According to my original plan, I would need to have this finished, and spend the next two weeks making the game interactive, meaning the player can break and pick up blocks. Luckily, I have removed that from my project because it is too ambitious, so I now have an extra couple of weeks to work on the enemies and the attack system of the player. In order to get on track, I think I will need to put in a little extra time outside of class.

So far what I've done on my project for Deliverable 4 is that I've improved the maze more by adding more features and fixing the environment of the game. As of Deliverable 3, I had made all the walls for the maze and added the texture to them. However, there wasn't a floor or a sky, or anything of an environment to the maze, so I needed to add that. First, I researched and learned how to use a sky in A-Frame, so I looked for a sky texture to use. Then, I needed to make it seem like the player wasn't just floating around inside the maze, so I researched how to add a ground to the maze and then did that. The other main thing I did was I slightly shaded some of the blocks that make up the walls of the maze, to make it seem more authentic and not just completely flat. I did this by adding a light gray color randomly to some blocks which kind of created the impression of texture. All of this I made using A-Frame. Here is how I added a sky to my maze. First, I imported the texture file into the project and then put this line of code:
```
<a-sky src="https://cdn.glitch.global/8abb628d-22c4-4bb8-aadf-810840838fc0/download.jpg?v=1650540758469"></a-sky>
```

Link to screencast explanation of Deliverable 4: https://youtu.be/5ZSs4y_VyLE



**Deliverable 3 -**
4 April, 2022

1. *What was your goal for this deliverable, as defined on your Learning Plan?*
2. My goal for this deliverable was to finish making the actual maze in the VR part of the game.
3. *Did you meet this goal? If not, why?*
4. Yes, I did meet my goal.
5. *What needs to happen for you to stay on schedule from this point forward (e.g., change of plan, putting in extra time, getting help, etc.)?*
6. I don't need to change anything for me to stay on schedule from now on. I just need to keep on working hard on my project during class. I need to keep my timeline and stick to the plan.

So far what I've done in Computer Coding 2 is that I've started to work on my project, both the beginning website and the maze itself. I've made the beginning website have the instructions so the players know what they're doing, and on a separate website, which is linked to the other with a Bootstrap button, I've used A-Frame to make the 3D maze. Since Deliverable 2, I haven't really worked on the introduction website and instead I have focused on coding in the blocks that make up the maze, as per my timeline. The shape of the maze is finished, meaning you can go through it and try to navigate it, though there are still some things I have to fix. I also added texture to the walls by importing an image of part of a wall into my project and putting it onto the maze. Coding the maze took a really long time to make, because, instead of making it out of rectangles or bigger shaped boxes for bigger sections of wall, I decided to do each block individually, in a maze that was 20 x 20. This ended up with me making almost 500 blocks and positioning them all in exactly the right way so the maze would turn out fine. Luckily I was able to copy and paste most of them and just change the positioning. Here is the code for just one box in the maze:
```
<a-box position="1 0.5 -3" src="https://cdn.glitch.global/8abb628d-22c4-4bb8-aadf-810840838fc0/Wall.jpg?v=1649488375908"></a-box>
```

Link to screencast explanation of Deliverable 3: https://youtu.be/GNS2DyrSyF4
  
  
  
**Deliverable 2 -**
6 March, 2022

1. *What was your goal for this deliverable, as defined on your Learning Plan?*
2. Create the landscape of the game by actually coding in the maze with textures.
3. *Did you meet this goal? If not, why?*
4. No, I wasn't able to meet this goal by the time of the deliverable. Instead of actually working on the maze, I diverged from my plan and instead focused on making the website that you visit in order to go to the maze. I wasn't planning on having this website, but realized I needed it to explain the game, the controls, and other aspects of the project.
5. *What needs to happen for you to stay on schedule from this point forward (e.g., change of plan, putting in extra time, getting help, etc.)?*
6. I think I need to stick to the plan in order to stay on schedule, and put in more time into the project. I also think that I would need to change the plan a little, because I've already gone away from it. I've decided that my goal of making the game more interactive through being able to place blocks was too ambitious would be way too complicated to do in a single semester. As a result, I'm changing that part of the plan so I can still complete the project.

So far what I've done in this class is I've started making my project. I've started using A-Frame to make my maze in VR, and I've relearned and reminded myself how to code using Javascript and HTML. After that, I started working on the actual website that will tell you the instructions for the game and will have the introduction. I also learned about CSS and how to use it, and how to use external, internal, and inline CSS in my HTML to make up the design of websites. I learned how to also use Bootstrap to make buttons on my website. That's mostly what I've done so far in computer coding 2. Example of using CSS to make a box with padding, a border, and centered in the middle of the screen:
```
div {
  width: 500px;
  border: 5px solid green;
  padding: 10px;
  margin: auto;
}
```

Link to screencast explanation of Deliverable 2: https://www.youtube.com/watch?v=N-YGU-v6Jpo
  
  
  
**Deliverable 1 -**
7 February, 2022

1. *What was your goal for this deliverable, as defined on your Learning Plan?*
2. Review my Javascript and HTML knowledge
3. *Did you meet this goal? If not, why?*
4. Yes, I remembered and researched on how Javascript and HTML work since it had been a while since I'd worked with either of them. I created a few lines of code with both with what I could remember, and learned or relearned other parts of code using CodeHS and the internet.
5. *What needs to happen for you to stay on schedule from this point forward (e.g., change of plan, putting in extra time, getting help, etc.)?*
6. Nothing really, I just need to keep working on my project consistently and follow my timeline that I created.

What I've learned so far for my project is mostly just relearning and reminding myself of how HTML and Javascript works, like tags in HTML or functions in Javascript, or just the format for either of them and how they work. I've also remembered how to use A-frame with HTML in Glitch to create a VR world where you can create shapes and move around in them. This is an example of HTML using A-frame where I created four cubes in different positions.
```
      <a-box position="-1 0.5 -1" color="#4CC3D9"></a-box>
      <a-box position="-1 1.5 -1" color="blue"></a-box>
      <a-box position="-1 2.5 -1" color="purple"></a-box>
      <a-box position="1 0.5 -1" color="#4CC3D9"></a-box>
```

