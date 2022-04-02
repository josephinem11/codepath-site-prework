# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Josephine Man**

Time spent: **5.5** hours spent in total

Link to project: (https://glitch.com/edit/#!/clever-befitting-pirate)

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

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![](https://i.imgur.com/9Y7y7Vc.gif) 

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
    W3Schools 

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
    A challenge I had encountered in creating this submission was writing the logic for the guess function and overall addressing the steps to take for our four cases—guessing incorrectly and thus losing the game, guessing correctly but still having remaining turns, guessing correctly but the turn isn’t over, and guessing correctly when the turn is over and is the last turn. Initially, I had trouble determining the logic for when a player has reached their last turn and set pattern less than or equal to 0 within my if statement. I soon realized that since the pattern was an array, I could use its length subtracted by 1 to reach the last turn. Though I didn’t come to this realization right away, I was able to get a better sense of the logic by drawing a diagram of hypothetical patterns on pen and paper. It soon became clear that if we equated the player’s progress to the last pattern in the game and the number of guesses to their progress, this would be indicative of the player’s win.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
 - What are some common JavaScript frameworks used in the tech industry?
 - How does JavaScript handle large data?
 - How would one enable a saving feature on a game like this?
 - How can a tool like MongoDB contribute to a game like this?

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
    If I had a few more hours to work on this project, I would like to implement difficulty levels of easy, medium, and level that would make the patterns increasingly harder to guess. Ideally, the player would be able to select their level of difficulty before starting the game. As each level of the game gets increasingly higher, I would decrease the milliseconds in the cluePauseTime and nextClueWaitTime constants. Additionally, to increase the stakes of the game, I would also like to add a timer/countdown at the corner of the game that would make each round last half a minute. If the player is unable to finish the game within the allotted time on the countdown, the player automatically loses.




## Interview Recording URL Link

[My 5-minute Interview Recording](https://vassar.zoom.us/rec/share/L8fDFvK-UaJdUOiTrAO5352EPvW2aQfiH9GkRRKUSVsXdjmDLQzzGdxaMwKAqSid.ljC3OWCvbXknJbc7?startTime=1648873605000 (Passcode: MW9^@wU1))


## License

    Copyright [Josephine Man]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
 
