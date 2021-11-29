https://trvler.netlify.app/

The purpose of this project was to better understand how APIs work. I used a RapidAPI account to pull data from a Travel Advisor API along with a weather API. I then integrated the data onto a list of restaurants, hotels, and attractions in the area. 

To make sure that the google maps API was relevant to the user, I created some bounds on the google maps API so that the travel advisor app wouldnt show restuarants outside of the user's area. I then used React useState and useEffect to refresh the map and the travel API everytime the user moved around the map or searched a new city. 

Then I moved onto building a few React components with Material Ui that would display cards containing information about any attraction in the area. I pulled the attractions name, rating, address, any awards, and contact information. 

Lastly, I added a weather API with rudementary icons to display local weather conditions. 

Technologies used for this were HTML, CSS, JavaScript, React, RapidAPI, and Material UI. 
