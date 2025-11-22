# AND101 Project 2 - Kotlin Debug-a-thon

Submitted by: **Aldo Socarras**

Time spent: **8** hours spent in total

## Summary

**Kotlin Debug-a-thon** is an android app that was riddled with some pretty nasty Kotlin bugs. With those gone, it's a collection of widgets for a variety of purposes! **I fixed the crash causing Context issues, repaired broken ConstraintLayouts, implemented logic for list processing, and revamped the Main Menu UI for better accessibility.**

If I had to describe this project in three (3) emojis, they would be: 🐛 🔨 🚀

## Application Features

The following REQUIRED features are completed:

- [x] 👋 Debug and fix navigation to Hello World activity
- [x] 4️⃣ Debug and fix Number Sum (2 + 2) activity
- [x] 📅 Debug and fix Current Day activity 
- [x] 🌈 Debug and fix behavior of Random Color activity
- [x] 🗒️ Debug and fix Print List activity
- [x] 💯 Debug and fix Favorite Number activity

The following STRETCH features are implemented:

- [ ] TODO

The following EXTRA features are implemented:

- [x] Redesigned `activity_main.xml` to use a `ScrollView` and `LinearLayout`, preventing buttons from disappearing on small screens.
- [x] Fixed internationalization warnings by using String placeholders (`%1$d`) in `NumSumActivity` instead of hardcoded text concatenation.
- [x] Fixed `AndroidManifest.xml` to correctly export the Main Activity while keeping sub-activities private.

## Video Demo

Here's a video / GIF that demos all of the app's implemented features:

<img src='https://imgur.com/a/ABoQgZA' title='Video Demo' width='' alt='Video Demo' />

GIF created with **Imgur**

## Notes

**Challenges & Fixes:**
* **Context Crash:** The biggest bug was in `MainActivity.kt` where `404 as Context` was being passed to the Intent. I fixed this by passing `this` (the Activity context).
* **Layout Issues:** Many XML files (like `activity_print_list.xml`) were missing Constraint anchors, causing views to collapse. I fixed this by adding start/end/top/bottom constraints and adjusting width attributes.
* **Logic:** Implemented `joinToString("\n")` to properly display the list of words in the Print List activity.
* **Manifest:** Resolved the "Intent Filter" error by updating the Manifest to register all new activities.

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
