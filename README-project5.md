# AND101 Project 5 - Choose Your Own API

Submitted by: **Kaylani James**

Time spent: **3** hours spent in total

## Summary

**Pokédex** is an android app that **fetches and displays random Pokémon from the PokéAPI. It retrieves the character's sprite, name, ID number, and weight, allowing users to "catch" a new random Pokémon with a button click.**

If I had to describe this project in three (3) emojis, they would be: 🔴 ⚡ 🐾

## Application Features

The following REQUIRED features are completed:

- [x] Make an API call to an API of your choice using AsyncHTTPClient
- [x] Display at least three (3) pieces of data for each API entry retrieved
  - I displayed the **Name**, **ID**, **Weight**, and **Image**.
- [x] A working Button requests a new API entry and updates the data displayed

The following STRETCH features are implemented:

- [ ] Add a query to the API request
  - The query I added is **FILL IN HERE**
- [ ] Build a UI to allow users to add that query

The following EXTRA features are implemented:

- [x] Used the **Glide** library to load the image URLs returned by the API into an ImageView.
- [x] Implemented logic to generate a random ID (1-898) to simulate "catching" a random Pokémon on every click.

## API Choice

My chosen API for this project is **The PokéAPI (https://pokeapi.co/)**.

## Video Demo

Here's a video / GIF that demos all of the app's implemented features:

<img src='(https://imgur.com/a/bBBsT9D)' title='Video Demo' width='' alt='Video Demo' />

GIF created with **LiceCap**

## Notes

In this project, I learned how to use `AsyncHTTPClient` to make GET requests to a REST API. A challenge I faced was parsing nested JSON objects (specifically accessing the `sprites` object to find the `front_default` image URL), but I resolved it by navigating the JSON tree step-by-step. I also learned how to use Glide to handle image loading asynchronously.

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
