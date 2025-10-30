# Project 4 - Memory Game

Submitted by: Daisi Perez

Memory Game is an app that allows users to play a fun and interactive game where they they match pairs of cards. If the cards have matching emojis, they disapear, if not, then they get flipped over again and the
user must continue finding its missing pair. This game's intended purpose is to challenge the users memory.

Time spent: 3 hours

## Required Features

The following **required** functionality is completed:

- [X] App loads to display a grid of cards initially placed face-down:
  - Upon launching the app, a grid of cards should be visible.
  - Cards are facedown to indicate the start of the game.
- [X] Users can tap cards to toggle their display between the back and the face: 
  - Tapping on a facedown card should flip it to reveal the front.
  - Tapping a second card that is not identical should flip both back down
- [X] When two matching cards are found, they both disappear from view:
  - Implement logic to check if two tapped cards match.
  - If they match, both cards should either disappear.
  - If they don't match, they should return to the facedown position.
- [X] User can reset the game and start a new game via a button:
  - Include a button that allows users to reset the game.
  - This button should shuffle the cards and reset any game-related state.
 
The following **optional** features are implemented:

- [ ] User can select number of pairs to play with (at least 2 unique values like 2 and 4).
  * (Hint: user Picker)
- [X] App allows for user to scroll to see pairs out of view.
  * (Hint: Use a Scrollview)
- [ ] Add any flavor you’d like to your UI with colored buttons or backgrounds, unique cards, etc. 
  * Enhance the visual appeal of the app with colored buttons, backgrounds, or unique card designs.
  * Consider using animations or transitions to make the user experience more engaging.

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app functionality!

## Video Walkthrough

https://youtu.be/wJlTC3QfqR8

## Notes

This project was defintely much easier than units 2 and 3. I faced very little issues while creating this app. Id say the only challenge was the UI but even then, it was pretty self explainatory since it was
all done on content view and not storyboard, which I struggled with a lot in the last two units.

## License

    Copyright [2025] [Daisi Perez]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
