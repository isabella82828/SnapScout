#  SnapScout

📌 Snapscout is a web app that scouts and navigates to photography hotspots in a city by leveraging scraping techniques with Python scripts, AWS, Socket.IO, and the Google Maps API.

## Features 

- Search Any Location: Enter your desired location using our autocomplete search or let the app detect your current location through our pinpoint feature.
- Discover Top Photography Spots: ShotSpot displays markers guiding you to the best photography spots in the area based on top Instagram posts.
- Contribute to the Community: If you find a fantastic spot that's not on the map, you can contribute by adding your own favorite locations to share with the photography community.

🛠️ A Python script is responsible for backend functionality by extracting popular photos from various locations, coupled with BeautifulSoup for web scraping, to obtain post IDs, precise latitude/longitude coordinates, and images. This information was converted to .json files and transmitted to AWS S3. 

🎨 The web application was configured with Express and Node.js as when the user enters their desired location, Express reads the .json file, the Socket.IO library transmits necessary information to the frontend, and integrated into the UI via the Google Maps API.

## Built with: 
* Python 
* HTML/CSS
* JavaScript
* Heroku
* React
* Node.js
* Express
* Socket.IO
* BeautifulSoup
* AWS S3
* Google Maps and Places API

