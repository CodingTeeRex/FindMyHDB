# Software Engineering Project - FindMyHDB

### ⚙️ Technologies Used:
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)

---

## Introduction

FindMyHDB is a web application developed using the Flask web framework. The application is recommended to be used on a PC, on browsers such as Firefox and Google Chrome for the best experience.

The application aims to facilitate the recommendation of the resale HDB flats and providing useful information to users based on the user’s specifications. Our goal is to design an intuitive system allowing customers searching for HDBs ease of access to the information they require, using the recommendation algorithm we have implemented. With our application, users may locate and search for HDBs based on their preferences. In addition, users have the option to contact the owners of the HDB listed on the application to discuss about their interest in the flat.

---

## Product Functions
This section provides a list of functions that is available within the application.

> 1. **HDB Recommendation:** Users can enter their ideal preferences for their perfect HDB. The recommendation algorithm will use these inputs provided by the user to match the users to a list of recommended HDB flats. <br/> <br/>
> The HDB recommendation takes into consideration these user preferences: <br/>
> &nbsp; &nbsp; **i.** The type of HDB flat (1-Room, 2-Room, etc.) <br/>
> &nbsp; &nbsp; **ii.** User’s budget <br/>
> &nbsp; &nbsp; **iii.** Nearby amenities <br/>
> &nbsp; &nbsp; **iv.** Distance away from amenity <br/>
> &nbsp; &nbsp;  **v.** Preferred location <br/>

> 2. **Display Amenities on Map:** After the list of recommendations are displayed to the user, users can choose to view more information about their recommendation. This function will display a static map which identifies all the nearby amenities specified by the user.

> 3. **Favorites:** Users are allowed to favorite different HDBs listed on the application. These favorited HDBs are stored in our database, respective to each individual’s account.

> 4. **Top picks:** Users will be greeted with a Top Picks page once they log into our system. This page shows the most favorited HDBs within our system.

> 5. **Compare:** Upon displaying the recommendations, the application provides an intuitive compare function which summarizes the important information from the results into a compact form for ease of readability and convenience.

---

## References and API
This section provides a list of APIs and references used in the project.
> 1. [Google Maps API](https://developers.google.com/maps/documentation/embed/get-started)
> 2. [Google Places API](https://developers.google.com/maps/documentation/places/web-service/overview)
> 3. [Google Geocoding API](https://developers.google.com/maps/documentation/geocoding/overview)
> 4. [Google Distance Matrix API](https://developers.google.com/maps/documentation/distance-matrix/overview)
> 5. [HDB Resale Flats Data](https://data.gov.sg/dataset/resale-flat-prices)
> 6. [Flask](https://flask.palletsprojects.com/en/2.0.x/)

---

## P.S. Application is not currently hosted on a server.
Included below are some images for illustration purposes.
![image1](imgformd/1.png)
![image2](imgformd/2.png)
![image3](imgformd/3.png)
![image4](imgformd/4.png)

---

### Credits
[Chen HongPo](https://github.com/pokerty) <br/>
[Ma JiaXin](https://github.com/Jiaxin0009) <br/>
[Reeves Chiu](https://github.com/Nydream) <br/>
[Jovian Lim](https://github.com/Kiriketsuki) <br/>
