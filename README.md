# 🏕YelpCamp
- Yelpcamp is a fully functional web application where users can create, review or delete campgrounds.  
- Users can upload pictures, leave reviews and ratings about campgrounds they visited and can check out other users post.  
# 📄Features
- New user needs to register and set up an account with an username and password.
- Once registered user can create new campgrounds and remove existing campgrounds.
- Users can leave, edit or remove reviews about a particular campground.
- Users can navigate on the map and see the campgrounds existing in that region.
# 🔨Tech-Stack  
### Frontend
- For Framework: [Bootstrap 5](https://getbootstrap.com/docs/5.0/getting-started/introduction/) 
- As template: [EJS](https://ejs.co/#docs)
### Backend
- For handling Server requests: [Node.js](https://nodejs.org/en/docs) along with [Express.js](https://expressjs.com/)
- As Database: [MongoDB](https://www.mongodb.com/) and [Cloudinary](https://cloudinary.com/)
- For API testing: [Postman](https://learning.postman.com/docs/introduction/overview/)
- For Authentcaion: [PassportJS](https://www.passportjs.org/docs/)
# 🌳Screenshots
#### Register Page
![Register](https://github.com/Tirtharaj-Talukdar/YelpCamp/assets/82752035/9de82324-8cc8-4b55-9823-3b21855e502d)
#### Login Page
![Login](https://github.com/Tirtharaj-Talukdar/YelpCamp/assets/82752035/24a6c89a-4bf8-4a20-975a-0332bd4a3882)
#### Home Page
![Homepage](https://github.com/Tirtharaj-Talukdar/YelpCamp/assets/82752035/3219eb18-eb01-4065-bce8-150bbbb76ae9)
#### All Campgrounds Page
![All-Campgrounds-2](https://github.com/Tirtharaj-Talukdar/YelpCamp/assets/82752035/56532f7b-a0f0-4a79-8a99-6b2741ff6823)
![All-Campgrounds-1](https://github.com/Tirtharaj-Talukdar/YelpCamp/assets/82752035/d96625d3-ce16-4a5b-928f-9dfaa00b4b4a)
#### Show Campground Page
![Show Campground](https://github.com/Tirtharaj-Talukdar/YelpCamp/assets/82752035/2d01660d-be1b-40f4-8f7d-51e38aaf0409)
#### Edit Campground Page
![Edit_campground](https://github.com/Tirtharaj-Talukdar/YelpCamp/assets/82752035/4f202f98-b162-4959-b2b6-d38f039dbbf6)
#### Leave Review Page
![Leave Review](https://github.com/Tirtharaj-Talukdar/YelpCamp/assets/82752035/ef06cb84-4fe4-49b3-8681-1c80c9eb0801)

# 💻Build and Run
### Prereuisites
#### Local Requirements
- Node
- Mongo
- Git
- Any Code Editor
#### Online Accounts and Access Keys
- Cloudinary
- MapBox
### Steps:
1) On the main repository, click the green Code button and copy the SSH.

2) Go or create a directory where you want the repository to be included then type this script on your terminal:

```git clone [SSH HERE]```  

3) Open the cloned repository on VS Code.

4) On your terminal, download all the dependencies by typing ```npm i``` or ```npm install```

5) Create a ```.env``` file to store the required keys for the project

6) replace value with the appropriate keys from the required accounts mentioned in the prerequisites
```
CLOUDINARY_CLOUD_NAME=[value]
CLOUDINARY_KEY=[value]
CLOUDINARY_SECRET=[value]
MAPBOX_TOKEN=[value]
API_KEY=[value]
OWNER_ID=[value]
```
7) Open a new terminal and type ```mongod``` to connect the projects on your local database. The project will not start until this is not opened ⚠️
8) Now to seeds your database, on the previous terminal, type
```node seeds/index.js```
(After getting a response of done on your terminal, wait for 3-8 seconds to let all the campgrounds' images get uploaded to cloudinary).
9) Hit CTRL+C to exit the current process.
10) Now, you are ready to run the program by typing either of the script on your terminal:  
```node app.js```  
or (recommended)
```
nodemon app.js
```
11. Once you see "Database connected", go to your preferred browser, then go to ```localhost:3000```






