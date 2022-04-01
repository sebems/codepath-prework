# Pre-work - _Memory Game_

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program.

Submitted by: **Sean Ebenmelu**

Time spent: **3** hours spent in total

Link to project: [Glitch Project](https://glitch.com/edit/#!/sideways-fishy-aardwolf)

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
- [x] Buttons use a pitch (frequency) other than the ones in the tutorial
- [x] More than 4 functional game buttons
- [ ] Playback speeds up on each turn
- [x] Computer picks a different pattern each time the game is played
- [x] Player only loses after 3 mistakes (instead of on the first mistake)
- [ ] Game button appearance change goes beyond color (e.g. add an image)
- [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
- [ ] User has a limited amount of time to enter their guess on each turn

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:

Win Sequence
![Win Sequence](https://cdn.glitch.global/fe78f387-1201-43b8-af7c-c2fe20158f32/win.gif?v=1648773257916)

Lose Sequence
![Lose Sequence](https://cdn.glitch.global/fe78f387-1201-43b8-af7c-c2fe20158f32/lose.gif?v=1648773266226)

## Reflection Questions

1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here.

   - W3Schools
   - Morzilla.org

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)

   - Implementing the strike mechanic. I tried to do it all in one night and I got a mind-block. I took a break from it and then revisited the problem with a fresh mind.
   And I then found that the problem wasn't that big of a deal. I figured that strike could only be counted if a failure occurs, which meant it needed to be put in the
   last else statement. Then I put an if-condition arround the loseGame() call, which will only activate when 3 strikes have been counted.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words)

   - How is animation done in web development? I've seen others make animations through JS. But how exactly woudl you go about
   importing or making the animation?

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words)

   - I would spend more time on the styling of the webpage, such as adding images to the buttons once they're clicked, or giving a different color scheme. 
   I would also like to add animations to the buttons.

## Interview Recording URL Link

[My 5-minute Interview Recording](https://www.loom.com/share/70a72188e3c744b78b85eb6038703a7b)

## License

    Copyright Sean Ebenmelu

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
