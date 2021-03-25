# Pre-work - _Memory Game_

**Rememory** is a Light & Sound Memory game to apply for CodePath's SITE Program.

Submitted by: **Noah**

Time spent: **~3** hours spent in total

Link to project: (https://glitch.com/edit/#!/power-graceful-coyote)

## Required Functionality

The following **required** functionality is complete:

- [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
- [x] "Start" button toggles between "Start" and "Stop" when clicked.
- [x] Game buttons each light up and play a sound when clicked.
- [x] Computer plays back sequence of clues including sound and visual cue for each button
- [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess.
- [x] User wins the game after guessing a complete pattern
- [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

- [x] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
- [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
- [ ] More than 4 functional game buttons
- [ ] Playback speeds up on each turn
- [ ] Computer picks a different pattern each time the game is played
- [ ] Player only loses after 3 mistakes (instead of on the first mistake)
- [ ] Game button appearance change goes beyond color (e.g. add an image)
- [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
- [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
Winning the game:
![](https://cdn.glitch.com/b506e726-6d7a-46aa-9cfa-5c6f9ba44b00%2FBetterRememoryGame.gif?v=1616635773061)
Losing the game:
![](https://cdn.glitch.com/b506e726-6d7a-46aa-9cfa-5c6f9ba44b00%2FBetterRememoryGame2.gif?v=1616635873054)
Start/Stop button functionality:
![](https://cdn.glitch.com/b506e726-6d7a-46aa-9cfa-5c6f9ba44b00%2FRememoryGame2.gif?v=1616634393665)

## Reflection Questions

1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here.
   Used StackOverflow to try and solve syntax errors that the IDE didn't notify me of.

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)
   -> JavaScript being slightly different than languages I'm used to, plus the lack of error detection in the IDE were both the biggest roadblocks in my completion of this project. For example, instead of "findElementById()", I typed "findElementbyId()".
   In case you don't see the difference(I didn't for quite some time), the "b" in the proper syntax is capitalized, which would have been key for the IDE to notify me of. Additionally, I found myself trying to use the size() function on the pattern array,
   and was confused as to why it wasn't executing the for loop. I now know that the length function is preferred in this language. Other than that, my little prior experience with HTML and CSS made this already-relatively-simple project go by that much more smoothly.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words)
   -> In regards to a relatively simple application like this game, I do not have too many questions. However, I have not yet gotten experience using JavaScript alongside SQL for database functionality. I have some experience with the Room library but would like to become more
   proficient at finding and using appropriate libraries on my own.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words)
   -> I would give it a more original design scheme, as well as replacing the tones with sound files(perhaps of xylophone tones). I would also add functionality to randomize the pattern at the start of every game, and add animations and more stylish messages for when the user wins or loses.

## License

    Copyright Noah

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
