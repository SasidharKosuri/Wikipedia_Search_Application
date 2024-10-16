# Wikipedia_Search_Application
This is a simple web application built with HTML, CSS, JavaScript, and Bootstrap. It allows users to search for Wikipedia articles using an external API and displays the search results with article titles, URLs, and descriptions.

# Features
- **Search Wikipedia Articles**: Users can type a keyword and press "Enter" to search for relevant Wikipedia articles.
- **Responsive Design**: Built using Bootstrap 4 for a clean, responsive layout.
- **Loading Spinner**: Shows a spinner while fetching results from the API.
- **Displays search results with**:
  - Article title (linked to the Wikipedia page)
  - URL of the article
  - A brief description

## How It Works
- The user types a keyword in the search input field.
- When the user presses the "Enter" key:
  - A spinner is shown to indicate that the app is fetching data.
  - The app makes a GET request to the Wikipedia search API.
- Once the results are fetched:
  - The spinner disappears.
  - The app displays the results, each consisting of the article title, URL, and description.
- If the user presses "Enter" without typing anything, no search is performed.

## Key Files:
- wik.html: The main HTML file that holds the structure of the app.  
- wik.css: The stylesheet that defines the custom design for the app.  
- wik.js: The JavaScript file containing all the logic for interacting with the Wikipedia API and rendering search results.  
