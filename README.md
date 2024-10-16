# Wikipedia_Search_Application
This is a simple web application built with HTML, CSS, JavaScript, and Bootstrap. <br>It allows users to search for Wikipedia articles using an external API and displays the search results with article titles, URLs, and descriptions.

<h2>Features</h2>
**Search Wikipedia Articles**: Users can type a keyword and press "Enter" to search for relevant Wikipedia articles.  

->Responsive Design: Built using Bootstrap 4 for a clean, responsive layout.<br>
->Loading Spinner: Shows a spinner while fetching results from the API.<br>
->Displays search results with:<br>
   --Article title (linked to the Wikipedia page)<br>
   --URL of the article<br>
   --A brief description<br>

<h2>How It Works</h2>
->The user types a keyword in the search input field.<br>
->When the user presses the "Enter" key:<br>
  --A spinner is shown to indicate that the app is fetching data.<br>
  --The app makes a GET request to the Wikipedia search API.<br>
->Once the results are fetched:<br>
  --The spinner disappears.<br>
  --The app displays the results, each consisting of the article title, URL, and description.<br>
->If the user presses "Enter" without typing anything, no search is performed.<br>
