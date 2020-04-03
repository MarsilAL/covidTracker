Covid Tracker Use Cases 

 

Use Cases: 

 

Online: 

            -   Primary Path: 

              1- The website is online ( the users can use it). 

        2- Use Case ends with Success. 

 

            -   Exception Path: 

              1- The website is not online ( the users can not use it). 

        2- Use Case ends with Failure. 

 

Register: 

            -   Primary Path: 

              1- Enter your User Name, Location, and Status. 

        2- Click Register button. 

        3- Registration for the database 

        4- Show the User Home page 

        5- Use Case ends with Success. 

 

            -   Exception Path: 

              1- One of the fields Username, Geolocation, or Status is empty. 

        2- Use Case ends with Failure. 

 

 

 

 

 

 

 

 

 

 

 

Check: 

            -   Primary Path: 

              1- Enter the User Status. 

        2- Click Check button. 

        3- Send the request to the database 

        4- Compare the user's geographic location data with the geographic location                  data of the users in the same area. 

        5- If there is a match, send a notification to the user with the number. 

        6- If there is no match, send a message to the user that the area is safe. 

        5- Use Case ends with Success. 

               

                -   Alternate Path: 

              1- The site asks the user to allow to get his geographical location. 

        2- The site automatically gets the user's geographical data. 

        3- Send the request to the database 

        4- Compare the user's geographic location data with the geographic                                 location data of the users in the same area. 

        5- If there is a match, send a notification to the user with the number. 

        6- If there is no match, send a message to the user that the area is safe. 

        5- Use Case ends with Success. 

 

 

            -   Exception Path: 

              1- The User has not entered the status 

        2- Use Case ends with Failure.(with error msg) 

 

 

 