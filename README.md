# 🧾 WebDev1 Pokémon Deck Storage

**A personal web-based storage and visualization tool for managing Pokémon TCG decks.**  
Created as part of a web development course project.

---

## 🔍 Overview

This site allows users (specifically Avi!) to store, organize, and visualize Pokémon TCG decks using dynamic API-powered visuals. Each deck is represented as a standalone page, dynamically loading card images and metadata from the [PokéTCG.io API](https://pokemontcg.io).

The project was built to practice:
- Semantic HTML and responsive layouts
- JavaScript DOM manipulation
- REST API integration
- Structuring modular web applications

---

## ✨ Features

- ✅ **Deck Viewer Pages** (`deck1.html` to `deck4.html`)  
  Each deck displays full card images, fetched live from the API.

- ✅ **Homepage Index (`index.html`)**  
  View all available decks with preview images.

- ✅ **Responsive Design**  
  Cards are displayed in a mobile-friendly, scrollable grid layout.

- ✅ **Semantic Markup**  
  HTML structure prioritizes clarity and accessibility.

---

## 🧠 Technologies Used

| Tech         | Usage                         |
|--------------|-------------------------------|
| HTML5        | Page structure                |
| CSS3         | Layout, card grid styling     |
| JavaScript   | DOM updates, API fetching     |
| PokéTCG API  | Card data & image rendering   |

---

## 🗂 File Structure

├── index.html # Main homepage with previews
├── deck1.html # Hop's Zacian ex deck
├── deck2.html # N's Zoroark ex deck
├── deck3.html # Dragapult ex control deck
├── deck4.html # Raging Bolt / Ogerpon deck
└── README.md # This file

---

## 🔐 API Integration

The site uses the **PokéTCG.io REST API v2** to fetch:
- Card names
- Set info
- High-resolution images

Each deck includes a JavaScript array of card objects like:

```js
{ id: "sv5-130", quantity: 3 }  // Dragapult ex


These IDs are passed to the API to load accurate card images.
