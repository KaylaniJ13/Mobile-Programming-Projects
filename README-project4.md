# AND101 Project 4 - CodeMath

Submitted by: **Kaylani James**

Time spent: **2** hours spent in total

## Summary

**Dog Age Calculator** is an android app that **allows users to input their age (or any human age) and performs a calculation to convert that number into "Dog Years." It demonstrates the use of input fields, button listeners, and mathematical logic within Kotlin.**

If I had to describe this project in three (3) emojis, they would be: 🐶 ✖️ 7️⃣

## Application Features

The following REQUIRED features are completed:

- [x] At least one (1) user input
  - Implemented an `EditText` with `inputType="number"` to accept human years.
- [x] At least one (1) interactive View
  - Implemented a `Button` with an `OnClickListener` to trigger the calculation logic.
- [x] At least one (1) output of a calculation based on the user input
  - Implemented a `TextView` that updates dynamically to show the result (Human Years * 7).

The following STRETCH features are implemented:

- [ ] Implement ViewBinding to reduce boilerplate code and increase efficiency
- [ ] Add at least one (1) additional functionality

The following EXTRA features are implemented:

- [x] Added Input Validation: The app checks if the input is empty and displays a **Toast** error message ("Please enter a number!") prevents the app from crashing.

## Video Demo

Here's a video / GIF that demos all of the app's implemented features:

<img src='(https://imgur.com/a/zTbkmwA)' title='Video Demo' width='' alt='Video Demo' />

GIF created with **Imgur**

## Notes

During this project, I learned how to capture user input from an `EditText` as a String and safely convert it into an Integer using `.toInt()` to perform math. I also learned the importance of input validation to ensure the app is robust and doesn't crash if the user clicks "Calculate" without typing anything.

## License

Copyright **2025** **Kaylani James**

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
