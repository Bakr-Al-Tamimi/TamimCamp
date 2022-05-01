# About TamimCamp 

TamimCamp was built for private educational and training purposes. This project follows from Colt Steele's 2021 web dev course on udemy.

## Purpose

This project was created using Node.js, Express, MongoDB, and Bootstrap. Passport.js was used to handle authentication.  

## Functionality

TamimCamp is a website where users can create and review campgrounds. In order to review or create a campground, you must have an account. 

## Features

* Users can create, edit, and remove campgrounds
* Users can review campgrounds once, and edit or remove their review
* User profiles include more information on the user (full name, email, phone, join date), their campgrounds, and the option to edit their profile or delete their account
* Search campground by name or location
* Sort campgrounds by highest rating, most reviewed, lowest price, or highest price

## Run it locally

1. Install [mongodb](https://www.mongodb.com/)
2. Create a cloudinary account to get an API key and secret code

```
# Clone TamimCamp
- Either use GitLab Git CLI: 
git clone https://github.com/Bakr-Al-Tamimi/TamimCamp.git
- or use GitHub GH CLI:
gh repo clone Bakr-Al-Tamimi/TamimCamp

# Install Project Dependencies
cd TamimCamp
npm install
```

Create a .env file (or just export manually in the terminal) in the root of the project and add the following:  

```
DATABASEURL='<url>'
API_KEY=''<key>
API_SECRET='<secret>'
```

# Run TamimCamp
Run ```mongod``` in another terminal and ```node app.js``` in the terminal with the project.  

Then go to [localhost:3000](http://localhost:3000/).

To get google maps working check [this](https://github.com/nax3t/google-maps-api) out.
