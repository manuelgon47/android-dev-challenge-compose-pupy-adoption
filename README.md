# Template repository

Template repository for the Jetpack Compose [#AndroidDevChallenge](https://developer.android.com/dev-challenge).

## Week #1 - Puppy adoption app
Let’s start the #AndroidDevChallenge with a bang bark: build a puppy adoption app! The app should contain an overview screen that displays a list of puppies, and a detail screen showing each puppy's details. You have until March 2nd, 23:59 PST to submit your entry. 2

Your UI must be fully built in Compose. Your submission will only be judged based on your app’s UI layer. To help you with the implementation, check out the Compose documentation on layouts, lists, text and navigation. For some paws-on learning try out the Compose pathway, with codelabs covering several topics useful in completing this challenge.

Are you a 🐱rather than a 🐶 person? Submissions for any type of pet adoption app are welcomed.

We look forward to seeing what you build!

## Getting started
Copy this repository by pressing the "Use this template" button in Github.
Clone your repository and open it in the latest [Android Studio (Canary build)](https://developer.android.com/studio/preview).

## Submission requirements
- Follow the challenge description on the project website: [developer.android.com/dev-challenge](https://developer.android.com/dev-challenge)
- All UI should be written using Jetpack Compose
- The Github Actions workflow should complete successfully
- Include two screenshots of your submission in the [results](results) folder. The names should be
  screenshot_1.png and screenshot_2.png.
- Include a screen record of your submission in the [results](results) folder. The name should be
  video.mp4
- Replace the contents of [README.md](README.md) with the contents of [README-template.md](README-template.md) and fill out the template.

## Code formatting
The CI uses [Spotless](https://github.com/diffplug/spotless) to check if your code is formatted correctly and contains the right licenses.
Internally, Spotless uses [ktlint](https://github.com/pinterest/ktlint) to check the formatting of your code.
To set up ktlint correctly with Android Studio, follow one of the [listed setup options](https://github.com/pinterest/ktlint#-with-intellij-idea).

Before committing your code, run `./gradlew app:spotlessApply` to automatically format your code.

## License
```
Copyright 2020 The Android Open Source Project

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    https://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
