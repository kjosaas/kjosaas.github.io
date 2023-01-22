# Deponika
Deponika is a web application that allows users to search for and view information about placement of archives. The application uses a JSON file containing data about these items and displays it in a table on the website.

The site is available from this link: http://dep.ikah.no/

The user can search for specific items by typing a query into the search box. The table will be updated in real-time as the user types, showing only rows that contain the search query in any of the columns.

When the user clicks on an ASTA-id in the first column of the table, the application opens a search on [Arkivportalen.no](http://www.arkivportalen.no) using the data in that cell. When the user clicks on Arkivskaper, the application opens a search on Digitalarkivet.no

## Getting Started
To use this application, you will need to have a web server running to serve the HTML, JavaScript, and CSS files, and also have access to the data.json file with the data you want to display in the table.

1. Clone or download the repository to your local machine.
2. Put all the files in the same directory on your web server.
3. Open the index.html file in a browser to access the application.
4. Modify the fetch request in the JavaScript code to point to the location of your data.json file on the server.

## Built With
- HTML
- CSS
- JavaScript

## Authors
Knut Kjosås - Initial work
