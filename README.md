# Pre-work - *Memory Game*

**Classic 1978 Simon** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Kyle Deveaux**

Time spent: **11** hours spent in total

Link to project: (https://glitch.com/edit/#!/six-deserted-tithonia?path=README.md%3A7%3A16)

## Required Functionality

The following **required** functionality is complete:

* [Y] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [Y] "Start" button toggles between "Start" and "Stop" when clicked. 
* [Y] Game buttons each light up and play a sound when clicked. 
* [Y] Computer plays back sequence of clues including sound and visual cue for each button
* [Y] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [Y] User wins the game after guessing a complete pattern
* [Y] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [N] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [Y] Buttons use a pitch (frequency) other than the ones in the tutorial
* [N] More than 4 functional game buttons
* [N] Playback speeds up on each turn
* [Y] Computer picks a different pattern each time the game is played
* [N] Player only loses after 3 mistakes (instead of on the first mistake)
* [N] Game button appearance change goes beyond color (e.g. add an image)
* [N] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [N] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!
          A count down
          Flasher header (rgb effect)
          putting the 4 character buttons in 1 circle. (giving a more traditional simon approach)
          A light show before the game starts 
## Video Walkthrough

Here's a walkthrough of implemented user stories:
![](your-link-here)





## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
https://ilovecoding.org/blog/js-cheatsheet

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

To begin, this is my first-time coding and learning JavaScript, HTML, and CSS. Most of my experience programming is in Python. 
Fortunately, I was able to rely on my logic background to be able to read and understand what was happening in the code. Therefore, my biggest challenge was learning the syntax. 
Luckily, by reading the explanations given in the prework along with some additional online help I was able to turn this project into my own. Additionally, 
in the final function which ultimately allowed the game to run, I ran into an issue where my nested if statements were not working and my game would fail after the fourth round. 
I knew that it had to be an issue with the counter because the game would announce my failure, which only occurs if it enters the lose 
game scenario in the final else statement. Meaning the counters were not matching and it was jumping to my final else scenario mid-game. After some debugging, I was able to realize that 
I failed to reset the counter after each turn and after that the game ran successfully. This project was very fun for me to do. It gave me the ability to learn in a very hands-on approach. 

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

One thing I learned about web developing during this project is that you must code simultaneously for both function and formatting. This is similar to GUIs in python where you program function and format the GUI in a separate window. 
Is web development always done in separate languages? Can you create a website through Python? If I wanted to create more complex online applications could I still use JavaScript or is it more tailored to directly functional programs or games? 
In the web development industry are projects completed more individually or more on a team basis? If so, are teams divided by feature and function or are they divided by language (ie. Javascript, CSS, HTML). 


4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

If given the opportunity to work on this project for a few more hours, I would try to change the visual design of the game. 
My vision for this game is to make it look exactly like Simon. I would have tried to place the 4 main buttons in a black circle giving a boarder look like the original Simon game. 
Likewise, it would have been great to place the start and stop buttons in the center of the game. 
In terms of functionality, I would go back and add a count down timer only giving the user 15 seconds to complete the given pattern; if the pattern is not complete in the given time then GAME OVER back to start. 
Additionally, if given more time I would have made an end game banner that persists. Once the user has completed the game and won, a special flash of colors would appear on the button.   



## License

    Copyright [Kyle Deveaux]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.