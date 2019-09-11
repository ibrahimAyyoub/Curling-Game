# Toronto Waste Lookup -Shopify Challenge 2019


# Description

Build a web app to search for waste items using the Toronto Waste Wizard database, and save frequently used ones.

# Instructions
- Reproduce the design as provided in the screenshot, which displays example search results.
- The data must be taken from the [Waste Wizard Lookup data (JSON)](https://www.toronto.ca/city-government/data-research-maps/open-data/open-data-catalogue/#5ed40494-a290-7807-d5da-09ab6a56fca2).
- Typing in the search field should *NOT* perform an API call.
- A search must be performed when hitting enter or clicking the search button.
- When the search input field is cleared, the list of results should also be cleared. 
- Performing a search should render a list of potential matching items based on keywords. Each item should:
   - Render the title and description of the item.
   - Render a grey star button *if the item is not already favourited*.
   - Render a green star icon *if the item is not already favourited*.
   - Clicking the star button should add the item to the favourites list.
- When the number of favourites is more than one, the app should render a list of items. Each saved item should:
   - Render the title and description of the item.
   - Render a green star button *if the item has been favourited*.
   - Clicking the green star button should remove the item from the saved list.
   
# Programming Languages/Frameworks/API's used:
   - Javascript(ES6)
   - Html5
   - Css3
   - Bootstrap
   - Fetch API(built in API)
# Testing/Deployment


- A link to a hosted version : https://ibrahimayyoub.com/WebEngineer/index.html
- Note! If for anyreason the hosted version isn't working, clone the repository and launch the index.html, it should be working just as fine.





Project: Assignment 3
Authors : Ibrahim Ayyoub, Id: 101080723 , email : ibrahimayyoub@cmail.carleton.ca
          Salim Erradi,   Id: 101071241 , email : salimerradi@cmail.carleton.ca
Node version: v8.11.4
OS tested : tested on MacOs High Sierra
install: npm install

Run and Test Instructions :
1. Download "A3" folder and unzip. 
2. Navigate to folder in cmd prompt. Path should be similar to C:\Users\Name\Downloads\A3\>
3. type the following, "npm install", in order to successfully install all libraries used(I only used socket io)
4. Use node server.js to start the server.
5. Type in http://localhost:3000/index.html in two separate browsers using ONLY google chrome.

NOTE PLEASE READ THIS IMPORTANT: 
I used a lot of ES6 features that are not available not Internet explorer/FireFox/Safari, sometimes the canvas's or stuff wont draw properly, 
So please use google Chrome only to test on different browsers.

Also don't make the browser minimized too small, because if you do its not gonna make the app run or start as intended,
so please start with a browser about a size of half of your screen, if you didn't thats fine, just refresh the browser on all clients.


6. Pick a username, and a colour(pick any colour that has a "name" and not RGB values, for example "green","yellow","blue","cyan","red","purple",etc)
7. Once you pick a username and colour, ready up on the current client, and then register on the other client.
8. Once you have ready up on both clients, press "start game" on either clients it will work either way. You need at least two
9. I made my shooting the stone in a "catapult style" , so please starting shooting from below the stone or beginning of the bottom of the stone.
10. Once you shoot the ball, both canvases update and the new motion is shown on all browsers that are watching.

11. the rest of the assignment is basically the physics part, which I don't need to explain since its shown.



Note:

Always open all browsers at the same time if you want to see the movements ,viewing, and in order to start the game you need at least 2 players. Follow the instructions above.