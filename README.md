# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Kevin Nguyen**

Time spent: **5** hours spent in total

Link to project: [Glitch project](https://glitch.com/edit/#!/clammy-pebble-pearl)

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
* [ ] Playback speeds up on each turn
* [x] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- None for now!

## Video Walkthrough

Showcasing Required Features:

### Full play through of default pattern with winning message
![Defualt Playthrough](/Gifs/full.gif)

### Losing message
![Losing the Game](/Gifs/lose.gif)

Showcasing optional Features:
### Random pattern on start
![Random](/Gifs/random.gif)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
Sites used for refrence include
- [MDN Web Docs](https://developer.mozilla.org/)
- [Markdown Guide](https://www.markdownguide.org/basic-syntax/)
- [w3schools](https://www.w3schools.com)
- [For note freq](https://www.seventhstring.com/resources/notefrequencies.html)
2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)
>When creating the submission one of those challenges was getting used to the syntax of JavaScript, HTML, and CSS. That was solved by rereading the 
instructions, consulting reference sites listed, or taking a look at the errors messages generated by the linter. One of the more frustrating errors 
encountered was entirely my fault and resulted in the incorrect logic while playing back the pattern. I had redeclared a global variable in a function 
rather than assigning it a value. After printing out messages in the console to try and figure out what was going wrong, I eventually looked at the code 
again and spotted the mistake. Figuring out the logic for the game logic was a bit tricky but was resolved by taking a look at the provided flowchart 
and taking a step back to review the logic behind the clue sequence played. Another problem found when developing on the chrome browser was that sometimes
the audio would not play. This was corrected by looking at the console messages and looking up the refrence for audio context.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
>One of the things I've noticed when learning about web development is the vast amount of libraries or plugins for JavaScript HTML/CSS. There is a lot 
to choose from so how would you figure out what to use or where to find it?\
Another thing would be how can developers ensure compatibility across different devices. Are there slight changes that can be made so that the website 
is displayed properly or will the styling have changed depending on the platform/browser?

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
>Some changes to enhance the user experience could be made if I were to spend more time on the project. For one, there isn't any indication of the round 
you are currently on despite a progress variable being used in the back end. Browser alerts are intrusive, so maybe a on screen animation/dialog could be 
created instead. User settings for the amount of rounds could be included since 8 rounds is quite long. Additionally, the options features meanted above 
are great additional features. Particularly with the timer and speed ups, the logic behind the playing of the clues was clever and allows easy changes to 
increase the difficulty. However, since tones are timer based, the tones will overlap if pressed too fast. A feature to prevent this could be added.



## License

    Copyright [Kevin Nguyen]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
