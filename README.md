# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Justin Chau

Time spent: 3 hours spent in total

Link to project: https://almondine-fringe-spot.glitch.me

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
* [x] More than 4 functional game buttons
* [x] Playback speeds up on each turn
* [x] Computer picks a different pattern each time the game is played
* [x] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![ezgif com-gif-maker-2](https://user-images.githubusercontent.com/86847268/158717787-971dcbd6-8ab3-4236-a253-35f065dedb53.gif)
![ezgif com-gif-maker copy](https://user-images.githubusercontent.com/86847268/158717792-e2ef581d-9789-4ff8-8eba-f390b32685a3.gif)
![ezgif com-gif-maker](https://user-images.githubusercontent.com/86847268/158717799-aef55490-d742-45a4-af14-09751727a1a5.gif)
![ezgif com-gif-maker](https://user-images.githubusercontent.com/86847268/159138419-13f32f81-8353-4296-a498-1a8bc3d275fa.gif)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
https://developer.mozilla.org/en-US/docs/web/javascript/reference/global_objects/math/random
https://javascript.plainenglish.io/how-to-generate-an-array-of-random-numbers-in-javascript-f883de667e84


2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? 
while working on this project some of the problems that occure are the syntex as i was more used to C++. however i notice that some things are similar to c++, i was able to use some of that knowledge in order to make the user to have 3 lives before losing. I had the most trouble when i was working on creating a random pattern every time. i understood how to do this in C++ and understood the concept but did not understand how to translate that to javascript, so i did a little bit research to find the code and how to implent it. Problems that started to occur when i did this was having it not having enought time to process the random Array, i sloved this by putting it in a function and calling it first, instead of trying to implent random array at the start button. i also had some problem figuring out how to clear an array but with some quick search was able to figure it out. another problem was having it glitch out by my random numbers put "0" when their is no zero button. took me some time to realize but the simple fix was to either make my random function then plus one to the product. however i just made it so that button 5 would be called zero instead, i think it worked better. i also had to fix things such as clueHoldTime, as this would not reset and made it super fast. fixed this by making it 1000 at the start. overall many of the problems that i faced could be sloved with more research online. 

3. What questions about web development do you have after completing your submission? 
Some questions that I have about web developer is this how most websites written with javascript, css and html? and how do websites connenet to severs in order to save information? also how do web developer remember all of these syntax of coding these differerent coding languages ? what are some ways i can improve my experience in coding ? 

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. 
if I had I few more hours I would use it to research on how to make a score tracker to keep the score and to keep the memory game infinitely, making it so it would display high score. I would also try to make the button pop up around the screen instead of the button becoming static. 




## Interview Recording URL Link

[My 5-minute Interview Recording](https://jjay-cuny.zoom.us/rec/share/mKoanMg_7nEVLbCoLhLsGGZdHcdAisacWSKQql4ouj72NTOb61Xo7fg4xbZ0zRP2.buLIlDg44Lzn4eUZ?startTime=1647399136000)


## License

    Copyright [Justin Chau]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
