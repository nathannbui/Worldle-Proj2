# ios101-project2-wordle-starter

# Project 2 - **Wordle**

Submitted by: **Nathan Bui**

**Wordle** is an app that lets users play a customizable version of Wordle, with settings to control word length, number of guesses, and themed word categories. An additional "Alien Wordle" mode increases the difficulty by resetting the goal word after every incorrect guess.

Time spent: **6-7** hours spent in total

---

## Required Features

The following **required** functionality is completed:

* [✅] User can change the number of letters per row (the length of the goal word)
* [✅] User can change the number of rows on the board (how many guesses allowed)
* [✅] User can select a new themed set to pull the goal word from
* [✅] User can select "Alien Wordle", causing the goal word to change after each guess

---

## Optional Features

The following **optional** features are implemented:

* [✅] App displays a reset button on the top left to reset the game (but make no changes to the settings)

---

## Additional Features

The following **additional** features are implemented:

* [ ] (You can add any extra enhancements here, for example:)
* [ ] Custom UI styling and colors for dark/light mode
* [ ] Animated keyboard and board feedback
* [ ] Score tracking for multiple rounds

---

## Video Walkthrough

Here is a Loom walkthrough of the app and its features:

<div>
    <a href="https://www.loom.com/share/aaf7a280447245029dd61c5ee9bbbcd1">
    </a>
    <a href="https://www.loom.com/share/aaf7a280447245029dd61c5ee9bbbcd1">
      <img style="max-width:300px;" src="https://cdn.loom.com/sessions/thumbnails/aaf7a280447245029dd61c5ee9bbbcd1-cf82b8225c8f9fb2-full-play.gif">
    </a>
  </div>

---

## Notes

* Biggest challenge was debugging `BoardController` after accidentally closing the class too early with an extra `}`.
* Also had to carefully unwrap optional values from the settings dictionary using the correct types (`Int`, `String`, and `Bool`) to prevent crashes.
* Learned how to use `UIBarButtonItem` to dynamically add navigation bar buttons for reset and settings.

---

## License

```
Copyright 2025 Nathan Bui

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```

---
