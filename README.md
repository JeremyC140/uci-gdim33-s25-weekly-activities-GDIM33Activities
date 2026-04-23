# GDIM 33 In-Class Activities
## W1
### Activity 1
1. My Moodboard

[Moodboard Link](https://docs.google.com/drawings/d/1X84hObsHi77y1mvDY4Q-7O0GRdMk-6aMNAHR06vlqzs/edit?usp=sharing)


2. Devlog Questions
- I am almost 100% committed to creating a rhythm game because it's my favorite genre of game. My initial inspiration on the game prototype is that: the rhythm game would blend the feeling of druming, have discernible VFX for different hitting types, and would hopefully be played on mobile. As for aesthetics, I included a lot of cute elements in the moodboard which I loved, and I might be working toward that direction (for the general aesthetics). 

- Chatted with table mate Averin and surprising found our shared interest in mobile rhythm games. This is encouraging for me in building my rhythm game and I would be happy to invite her to playtest my game throughout the development. 

- Discussed with LA Elijah! He didn't play much rhythm game but he thought my idea of a mobile rhythm game would be cool. 


### Activity 2
<img width="960" height="720" alt="GDIM 33 Rhythm Game Break-down (1)" src="https://github.com/user-attachments/assets/a0cc965b-7396-4d07-8e28-3984b90fc5de" />


## W3
### Activity 1
<img width="1072" height="694" alt="image" src="https://github.com/user-attachments/assets/40ae40cd-4cfc-4e0c-85b4-4e0cf98a4190" />


### Activity 2
1. It's more advantageous to save the event name as a scene variable because it provides easy access to the event variable across different visual scripting graphs, rather than coder trying hard to memorize every event name they created. 

2. Using debug.log helps me to check that a specific node has been runned without struggling to observe both the scene play and the visual scripting graph at the same time (which could be hard on my screen). The linear progression of visual scripting graph also makes it certain that its previous node has been visited which is definitely helpful for efficient debugging. 

3. Set cursor lock state would be somehow relevant to my vertical slice because my current rhythm game operates based on player's keyboard input, without using the mouse. However, since my rhythm game is a 2D lock-screen game, player moving the cursor wouldn't actually affect the gameplay. Thus, it's a feature that's optional for me to implement. 

4. Certainly! The concept of game state would help me manage the switch of scene before game, during gameplay, and after gameplay (the result scene). It would also be another good usage of scripting state machine in my game. 


## W4
### Activity 1
For this current build, there's the basic layout of the in-game screen design (the star pattern) with combo text that won't update yet. The song starts when the game starts and could be paused (esc / p) or resumed (z). There's no music notes automatically coming out yet but pressing keyboard 1 ~ 7 would spawn notes on the stars respectively (for testing purpose)(visualize how golden star "float" out of the silver star lanes). The judgment system is also implemented but only work in engine (only debug.log hint for judgment result). 
My playtesting goals mostly centered around visual and experience feedback, including how player think about the "R, F, V, Space, I, J, N" finger position, how visually convincing is the "approaching" effect, and how visible are the music notes. 

Playtest Team: Ke-Chieh Chang (me), Jingyi Cheng, Jeremiah Yang, Brandon Tsay

Since there aren't really gameplay in my game, so I introduced to them about the features I've implemented for now (mostly as described above). For the finger position, they could see the logical intuition I'm trying to map with the star pattern to the keyboard, but they feel it's best for the key position to be customizable (which will be in the future). For the visual effect, they suggest to extend the silver star to the back to look like a "lane", and also adding some animation on both stars and the background to feel the "groove" better. Furthermore, I will certainly be adding visual guide on each of the star that writes the corresponding key mapping to them in order for player to explore and play the game on their own in the future, without guidance. 
