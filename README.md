# Nearby Hospital and Park Finder

## Project Overview
The **Nearby Hospital and Park Finder** is a web application that allows users to find hospitals and parks within a specified radius on Google Maps. The frontend is built using **HTML, CSS, and JavaScript**, and the app uses the **Google Maps API** to display locations dynamically.  

Users can:
- Search for nearby hospitals or parks.
- Specify the radius for the search.
- View all results on an interactive map.

The entire code is in **one file**: `index.html`. An example output is provided below.

---

## Features
- Interactive Google Maps integration.
- Dynamic search for hospitals and parks within a radius.
- User-friendly design using HTML, CSS, and JavaScript.
- Entire project contained in a single HTML file for easy deployment.

---

## Technologies Used
- HTML5
- CSS3
- JavaScript (Vanilla JS)
- Google Maps JavaScript API
- Google Places API

---

## How to Use
1. Open `index.html` in any modern browser.
2. The map will display your current location.
3. Enter the radius in meters.
4. Click **Search Hospitals** or **Search Parks**.
5. Nearby locations will appear as markers on the map.

---

## Steps to Replace Your Google Maps API Key
1. Obtain a Google Maps API key:
   - Go to [Google Cloud Console](https://console.cloud.google.com/).
   - Create a new project or select an existing one.
   - Enable **Maps JavaScript API** and **Places API**.
   - Generate an API key.
2. Open `index.html` in a text editor.
3. Locate this line near the bottom of the file:
   ```html
   <script src="https://maps.googleapis.com/maps/api/js?key=YOUR_API_KEY&libraries=places"></script>
