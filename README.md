# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Samya Ahsan

Time spent: 5 hours spent in total

Link to project: https://glitch.com/edit/#!/checker-rainbow-notify?path=index.html%3A1%3A0

## Required Functionality

The following **required** functionality is complete:

* [X] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [X] "Start" button toggles between "Start" and "Stop" when clicked. 
* [X] Game buttons each light up and play a sound when clicked. 
* [X] Computer plays back sequence of clues including sound and visual cue for each button
* [X] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [X] User wins the game after guessing a complete pattern
* [X] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

## Video Walkthrough (GIF)

![Game Won](https://i.imgur.com/FyxAvMl.gif)
![Game Lost]!(https://i.imgur.com/osZ9wjW.gif)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
N/A

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)
Managing several different moving parts in languages that I have not used before for a good amount of time proved to be challenging at times. However, the challenge provided a great opportunity to grow as a programmer. As I was following along the instructions, it was easy to believe that I knew what each line of code was doing. However, when it came to programming my own guess() function, I realized that I needed to inspect the code more carefully, especially the sound synthesis functions, to better understand what I was coding and to produce a well-working function. So, I first went through the existing code, applying a level of abstraction such that I could understand how all the parts worked together even if I didn’t completely understand the implementations. Then – after gathering this birds-eye view of the codebase – I went line-by-line through each function, learning what it was doing, the Javascript syntax, and when (and why!) it called other functions. From here, I was able to better understand how the code worked and how to approach the guess() function, as well as picking up some JavaScript along the way. 

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
Coding this project helped me realize how little front-end development I knew, and also how much fun I was missing out on! Much of my courses and extracurriculars involve low-level and back-end programming - such as in my research lab, where I work closer with hardware to automate 3D printing food. While I find that type of programming very interesting and satisfying, this project showed a different aspect to coding that I haven’t explored much of before, and that I’m excited to learn more about! How can I build a website to fit different needs, such as a personal website, or a website for my projects in my research lab? What differentiates good design from bad design? How would the design of the site be considered? If I wanted to create a leaderboard for the game so that players globally could compete against each other, would I need a database for that? How would I integrate a database with my website? While this project is far from the advanced, modern web dev project I see today, each component opened a new avenue of curiosity for me: how does this work, how could I improve it, and what else is out there that I could integrate into my project (or spur the creation of new one!)? 

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
I would like to modify the game to add musicality such that a user can choose different versions (e.g. retro, classical, disco) to play: so, the game button sounds would be modified to include an audio file. I would also like to include a leaderboard so that players could remotely compete against each other. It would also be interesting to have the user be able to pick different “eras” of the website: for example, the user could select a “90s” option and have a 1998 version of the website show, and have the game include sound bits from popular songs from that era. Doing so would be an interesting exercise not only in programming, but in how web design has evolved over the years and why certain features have changed in favor of newer ones. While I don’t have the skillset or the time at this moment to implement these features, I look forward to learning enough to make these design daydreams into deployable features!


## Interview Recording URL Link

[My 5-minute Interview Recording](https://www.dropbox.com/s/udfomwluszodo76/video5759334051.mp4?dl=0)


## License

    Copyright Samya Ahsan

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
