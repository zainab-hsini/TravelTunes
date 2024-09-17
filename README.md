# TravelTunes

**TravelTunes** is a Python-based application that generates a custom playlist for your trip based on the duration of your journey. Using the Spotify API, it provides music recommendations according to the genre you choose and ensures the playlist duration matches your trip time.

## Description

**TravelTunes** helps you make your trips more enjoyable by automatically creating a playlist that fits the duration of your journey. Simply input your departure and arrival coordinates, choose a music genre, and let the application generate a playlist with the right length and musical style for your travel.

## Features

- Calculates the duration of your trip using GPS coordinates.
- Trip duration is calculated using "Driving Mode".
- Fetches music recommendations from Spotify based on the chosen genre.
- Generates a playlist with tracks that add up to the trip duration.
- Displays the playlist with track names and artists.

## APIs Used

### 1. **TravelTime API**

- **Purpose**: Calculates the travel time between two locations based on GPS coordinates.
- **Why Chosen**: Provides accurate travel time estimation using different transportation modes. 
- **Limitations**: Limited to locations within the United Kingdom. 

### 2. **Spotify Web API**

- **Purpose**: Fetches track recommendations based on a genre and retrieves detailed information about tracks.
- **Why Chosen**: Offers extensive music data and recommendations, allowing us to generate a playlist that fits the desired genre.
- **Limitations**: The available genres are limited to 20, offering a broad but somewhat generalized range of options.

## How to use the program
- Click on the "Open in Colab" tab at the top of the program in the "TravelTunes.ipnyb" file.
- Get the API keys:
  - Go to Spotify Developer Dashboard.
  - Log in and create a new application.
  - Copy your Client ID and Client Secret from the app you created.
  - Go to TravelTime API Developer Portal.
  - Sign up for an account and get your credentials.
- Run the first and second code cell.
- Follow the description displayed: enter the coordinates of your location first, latitude then longitude, then those of your destination.
- Run the third code cell
- Follow the description displayed: choose from our selection of 20 genres your preferred genre, and enter its name.
- A playlist should be displayed on your screen by now. Have a good trip!
