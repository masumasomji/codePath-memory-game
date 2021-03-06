# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Masuma Somji**

Time spent: **6** hours spent in total

Link to project: https://glitch.com/edit/#!/south-sprout-tie

## Required Functionality

The following **required** functionality is complete:

* [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [x] "Start" button toggles between "Start" and "Stop" when clicked. 
* [x] Game buttons each light up and play a sound when clicked. 
* [x] Computer plays back sequence of clues including sound and visual cue for each button
* [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [x] User wins the game after guessing a complete pattern
* [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [x] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [x] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
http://g.recordit.co/d8oU3Y0VJ3.gif

<img src="http://g.recordit.co/d8oU3Y0VJ3.gif" width=250><br>

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
**I used most of the resources provided in the prework assignment as they really helped me understand more about these languages. Here are some of them:
Rapid Tables - CSS Color, cssreference.io, w3schools.com**

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
**One of the errors that I kept having was when handling guesses. In my initial version of the guess function, I had it so that in the initial for loop, it would first
check if the guessCounter wasn't yet equal to the progress, it would add to the guessCounter and the else statement was set so that if the guessCounter was equal to progress,
then only it would play the next pattern. Because of this, the sound on the buttons wasn't working anymore and I realized I had the order of the if-else statement switched so 
I set so it would first check if the guessCounter WAS equal to the progress and therefore, play the next segment and continue the game.**

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
**I would love to know more about the best practices to make a page load faster without compromising the features, how to better organize classes and functions as it relates to
the development of the page across multiple individuals, and more about SQL. I'm also very interested in web design and different features for the overall aesthetic of a webpage/
how to make the experience for a user as flawless as possible from the programming side of things.**

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
**If I had more time, the first additional feature that I would implement is definitely making it a different pattern in every game and making the computer randomize each sequence.
As someone who is taking Data Science, we often use the inbuilt functions to analyze data and I think it would be very insightful to actually have a feature that would measure
how many times the user lost at a specific point in the game (determine whether it was always after the same number of steps or otherwise) and drawing basic insights/projections
from the user's own experience. I'd also like to see how having a limited time feature affects the performance of the user and whether it makes it more likely for the user to lose
or not. Drawing conclusions from the data can then help optimize the app for a better experience.**



## License

    Copyright [Masuma Somji]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
