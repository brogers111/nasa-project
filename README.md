# NASA Launch Project

## Description

This web application uses the SpaceX API to display historic launches and allows users to plan their own launches based on launch date, mission name, rocket type, and destination (if any). The potential destinations are being pulled from a CSV export of Kepler Exoplanets from the NASA expolanet archive and populated in a MongoDB database using the NodeJS CSV-Parser module. Axios is used to pull SpaceX launch data and populate within the database.

## Project Design

<img width="1051" alt="Screenshot 2025-03-23 at 8 12 47 PM" src="https://github.com/user-attachments/assets/36551373-abbe-4e74-9c32-bb6535b5b60e" />
<img width="988" alt="Screenshot 2025-03-23 at 8 13 00 PM" src="https://github.com/user-attachments/assets/3e349379-90b7-44af-8d86-874e438e9b58" />


## Tech Stack

- React
- NodeJS
- Express
- PM2
- Axios
- MongoDB
- Mongoose
- Morgan
- Arwes

## Deployment

To view the application run:

<code>npm install</code>
<br>
Then run:
<code>npm run deploy</code>
  
## Future Improvements

- Add new launch form inputs such as rockets and payload
- Add hyperlinks to planet and launch details
