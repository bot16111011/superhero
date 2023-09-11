# superhero

steps to make superhero hunter app
1> Get api key from https://developer.marvel.com/signup, make a working url by using ts=1, public key and private key
2> Create Html files: index, favourites, comics,heros htmls
    It includes a Bootstrap-based navigation bar with links to "Home," "Heroes," and "Favorites." 
    The index page also features a search bar for searching superheroes, and it imports various JavaScript files for application functionality, including secret data handling, interaction with the Marvel API, managing favorites, and the main application logic.
    Favourites has the content section displays favorite heroes and comics.
    The character page displays character details and the comics in which the character is featured.
    The comic page displays details of outline of the comic 

3> I have created a single css file named styles.css where all the styleing is done
    This CSS code defines the styling for a superhero-themed website. 
    It creates a dynamic and visually appealing design with features like a hero image background, character cards, a search bar, and favorite buttons. 
    The design includes hover effects for character cards, scrollbar customization, and responsive adjustments for smaller screens. 
    The overall style reflects a dark and immersive superhero theme with attention to detail in layout, color, and interactive elements.

4> Create javascripts file, here I have created 7 js files:
    index.js,secret.js,marvelAPI.js,favourites.js,favourit_page.js,character.js and comic.js
    a) marvelAPi.js: This code defines the Marvel API URL and a function to fetch data from it using an API key and hash, ensuring secure access to Marvel's data.
    b) secret.js: This file was used to save public key and md5 hash after generating it using public key, timestamp and private key
    c) index.js: This JavaScript code controls the functionality of a superhero-themed website. 
       It handles dynamic search suggestions as users type in the search bar, displays character and comic cards, and allows users to mark their favorites. 
       Additionally, it enables redirection to detailed character pages based on user selections and efficiently populates the web page with data fetched from the Marvel API.
    d) character.js: This JavaScript code retrieves a character's details and related comics from the Marvel API based on the character's ID obtained from the URL. 
       It also handles marking and unmarking characters as favorites in local storage and displays the character's information and comics.
    e) favourite.js: This JavaScript code manages the functionality for toggling characters and comics as favorites. 
       It stores favorite items in local storage, updates the UI accordingly, and provides event listeners for clicking on favorite buttons or character cards, allowing users to add or remove favorites and redirect to character details.
    f) favourite_page.js: This JavaScript code handles the display of favorite characters and comics on a web page by fetching their details from the Marvel API based on stored IDs in local storage. It also provides a message if there are no favorites to display.
    g) comic.js: This JavaScript code retrieves and displays comic details and related characters from the Marvel API based on the comic's ID obtained from the URL parameters. It also allows users to toggle comic favorites, and it checks and updates their favorite status.

      
