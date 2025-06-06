# Pokemon-Searching-Engine


This project has 4 files:

index.html
This is the main page.
It shows a form for searching Pokemon.
It displays search results with cards.
Each card has a like button to save a Pokemon.
There are filters for types and abilities.
There is a Pokeball icon in the corner that shows saved Pokemon when hovered.

inventory.html
This is the inventory page.
It shows the list of liked Pokemon saved in localStorage.
It has buttons to sort the list by ID, Name, or Ability.
There is also a download button to save the list as a JSON file.
A side menu helps to go back to the main page.

index.css
This file contains the styles for both pages.
It defines the layout of cards, buttons, menu, loader, and responsive design.

index.js
This is the JavaScript file for both pages.
It checks the body id to know which page is open.


If the page is main_page:
It loads Pokemon types and abilities.
It searches and displays Pokemon based on user input.
It saves liked Pokemon to localStorage.

If the page is inventory_page:
It loads the saved Pokemon from localStorage.
It displays them in the result area.
It lets the user sort the list.
It allows downloading the list as a JSON file.

Main features:
User can like Pokemon on the main page.
Liked Pokemon are saved and shown in the inventory.
User can sort and download the list.
