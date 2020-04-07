Covid Tracker Use Cases 
========================
 

Register
--------
 
__Synopsis:__
A user registers to become a user of the covid tracker app.
 
__Precondition:__
- User is not known to the system
 
__Actors:__
user, system
 
__Trigger:__
- User visits the website
 
__Primary Path:__ 
- User enters Username, and Status 
- User issues the register command 
- System creates a new user entry and stores the information given by user 
- System shows the User Home screen 
 
__Exception Path:__ 
- One of the fields Username,Status is empty. 
- Show error message, required information must be entered 



Check
--------
__Synopsis:__ 
- The user is allowed to send his location information to the site to check for the presence of Corona in his area 

__Precondition:__ 

- User’s geolocation is not known to the system 

__Actors:__
- system 

__Trigger:__ 

- User click on allow button To allow the website to get  the information 

__Primary Path:__ 

- The site asks to allow access to data  

- User Click Allow button 

- User issues the Allow command  

- System creates a new geolocation entry and stores the information given by user  

- System shows the User result screen  

__Exception Path:__

- The user refuses to allow the site to access the data.  

- Show error message, required to access geolocation information for Check 

  