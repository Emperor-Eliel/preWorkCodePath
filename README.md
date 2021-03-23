# Pre-work - *PhotoSonic Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Eliel Davis**

Time spent: **4** hours spent in total

Link to project: (insert your link here, should start with https://quaint-meowing-doom.glitch.me)

## Required Functionality

The following **required** functionality is complete:

* [ x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [ x] "Start" button toggles between "Start" and "Stop" when clicked. 
* [ x] Game buttons each light up and play a sound when clicked. 
* [x ] Computer plays back sequence of clues including sound and visual cue for each button
* [ x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [x ] User wins the game after guessing a complete pattern
* [x ] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [x ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [x ] Computer picks a different pattern each time the game is played
* [x ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![]()


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
[https://stackoverflow.com/questions/1527803/generating-random-whole-numbers-in-javascript-in-a-specific-range]

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
[Although I'd love to say this project was without its challenges, I definitely had to really think about some of the steps.  I noticed while trying to randomize the button pattern, that the function I was using included the integer zero.  I used this code that was on stackoverflow, but with the use of an if else statement I was able to exclude integers out of the range.  I found that the ability to synthesize outside resources and my own ideas helped me to overcome that challenge.  I also have not used JavaScript  in quite some time.  I’m glad the instructions were very clear and helpful. ]

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
[How is web development connected to other categories of coding?  For example, how does web design and database development intersect? Will web development be like this activity in the future?  Is frontend, backend or full stack most valuable when designing a website?  Is web development fundamentally different from app development?  Are the skills learned in web development translational to skills in app development and vice versa? ]

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
[I would add different difficulties to the game.  I would have one version where the user can see all of the buttons the whole game, and a harder version where the buttons are only visible when showing the pattern and when you press.  This would make the user depend on memory more to solve the game.  I would strategically hide and show buttons so that they make a path, and the pattern represents a path across panels.  I would enhance the buttons futher as well.]



## License

    Copyright [Eliel Davis]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
