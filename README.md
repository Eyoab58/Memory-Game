# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Eyoab Asrat**

Time spent: **4** hours spent in total

Link to project: (insert your link here, should start with https://glitch.com/edit/#!/foremost-inquisitive-lake?path=index.html%3A1%3A0)

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

* [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [x] Buttons use a pitch (frequency) other than the ones in the tutorial
* [x] More than 4 functional game buttons
* [x] Playback speeds up on each turn
* [x] Computer picks a different pattern each time the game is played
* [x] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn


## Video Walkthrough

Here's a walkthrough of implemented user stories:
![](http://g.recordit.co/xBeguLn3km.gif)
![](http://g.recordit.co/zFAXx9W3WA.gif)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
  I  used Stack Overflow to get a better understanding behind how I was supposed to utilize _Math.Random_ in order to randomize the array of patterns

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

 The most challenging aspect about this project that I had to encounter was the randomization of the pattern array within the JavaScript class. My first instinct was to use some form of a loop to copy over the array in some ordered fashion. It was until when I had read the tip given in the instruction to utilize _Math.Random_ when sorting the array of patterns that things began to get tricky. At first I wasn't too familiar with the function _Math.Random_. However after some time looking into the functionality of it on the website _Stack Overflow_ I had soon realized that it is very similar to that of the Math class in Java. Due to my previous background in Java I am well rounded in the language, and it was a pleasant surprise to find that it was something that I had already known how to implement. Once I had understood that everything else became clear from there. I find it important that when dealing with a forein concept similar to that it is important  to not panic and to be persistent in understanding the concept. I was fortunate enough to have some understanding prior to starting this project, which ultimately had aided me to pass through the obstacle.


3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

[This project opened up my eyes to a multi-layered project. I am still growing as a computer scientist, so I am always open to learning more about different languages as I grow. With the being said, this was my first opportunity to see how a multitude of languages can all work together in order to create a singular project. However, with that comes quite a few questions in regards to how the languages work together. For example, is having multiple languages embedded on a singular project the most efficient? Unless there is a specific action or attribute that only a specific language can provide, I don’t see much of a need for projects that have a combination of languages. I’d like to believe that a lot of this can be implemented using JavaFx.] 

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

[If I had a few more hours to work on this project I would definitely attempt to change up the button configuration as well as the sound. Learning about how the shapes were constructed was interesting, but I think it would have been cool to see some movement with the buttons. What I had in mind was that the buttons change shape while the pattern sequence is being displayed. It would have been a neat trick to implement to throw the user off. However, looking back at it I can see the complexity behind that concept and how troublesome it might be. Alongside that, I was upset that I didn’t get the chance to manipulate the audio of the buttons. I feel as if having some noise other than the high frequencies would’ve been cool to see. Finally I would have spent more time finding a more efficient way to increase the speed of the _clueHoldTime_, because what I had done was simply plugged-and-chugged, different values within the function to see what had worked best.]



## License

    Copyright [Eyoab Asrat]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
