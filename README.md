This project uses the popular NASA Astronomy Picture of the Day open API to produce wonderful images with details and lengthy descriptions which the users can scroll through and save to the favorites collection.

Built with vanilla JavaScript, HTML and pure CSS. 

Functionality:

🚀 the app displays random Astronomy Pictures formated into cards with an image, title, "add to favorites" star button, description, date and copyright information

🚀 the app displays 10 new images after every loading

🚀 images are lazy-loaded to improve performance - the app will load the image only when it comes close to being scrolled to

🚀 clicking on an image opens the full resolution of that image in a separate tab

🚀 the user can add and remove images to and from the "favorites page," which stores images using local storage

🚀 the app is mobile responsive


The app uses responsive design to be both mobile and desktop friendly. 

HTTP Request

GET https://api.nasa.gov/planetary/apod

from: 

https://api.nasa.gov/

Live demo: 

https://nasa-apod-application.netlify.app/
