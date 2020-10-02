# DataSelfieApp

## Working link: https://serene-edison-888668.netlify.app
### NOTE: This app is hosted on Netlify which doesn't have support for neDB database. To make this app work properly while hosted you'll need to change the database to mongoDB atlas or something similar to it.

This App lets you capture yourself using your laptop's webcam and stores it along with the coordinates of your place.

It lets you capture yourself using your laptop's webcam along with your name and location (latitude and longitude). This will be stored in the database and you can see them anytime you want.

It uses p5.js library for capturing the pictures using your webcam. Ofcourse, it will ask for the permission. While capturing, it will also geolocate your position(latitude and longitude). It will store the data in database and you can see the pictures, location and your name there.

This project also has a subtle interface to make it intuitive to use.

### To Run
1) npm install
2) npm run start
