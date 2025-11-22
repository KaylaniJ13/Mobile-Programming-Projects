# AND101 Project 6 - CYOAPI Part 2: RecyclerView Edition

Submitted by: **Kaylani James**

Time spent: **4** hours spent in total

## Summary

**Pokédex List** is an android app that **fetches a list of 20 Pokémon from the PokéAPI and displays them in a scrollable RecyclerView. Each item includes the Pokémon's name, ID number, and sprite image.**

If I had to describe this project in three (3) emojis, they would be: 📜 🐉 📱

## Application Features

The following REQUIRED features are completed:

- [x] Make an API call to an API of your choice using AsyncHTTPClient
- [x] Implement a RecyclerView to display a list of entries from the API
- [x] Display at least three (3) pieces of data for each RecyclerView item
  - I displayed the **Sprite Image**, **Name**, and **Pokedex ID**.

The following STRETCH features are implemented:

- [ ] Add a UI element for the user to interact with API further
- [ ] Show a `Toast` or `Snackbar` when an item is clicked
- [ ] Add item dividers with `DividerItemDecoration`

The following EXTRA features are implemented:

- [x] Implemented string manipulation to extract the Pokémon ID from the API detail URL to construct the image URL manually, saving unnecessary network calls.
- [x] Styled the RecyclerView rows with a custom "Red Card" design to mimic a physical Pokédex.

## Video Demo

Here's a video / GIF that demos all of the app's implemented features:

<img src='(https://imgur.com/a/967rLqI)' title='Video Demo' width='' alt='Video Demo' />

GIF created with **Imgur**

## Notes

The main challenge was that the PokeAPI list endpoint (`/pokemon?limit=20`) does not provide image URLs. I had to learn how to split the detail string (`.../pokemon/25/`) to extract the ID (`25`) and then manually build the official sprite URL string to pass to Glide.

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
