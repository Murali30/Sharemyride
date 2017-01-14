# Sharemyride
To install and run the application:
1. Install all the required packages using npm install command.
2. Start the mongodb.
3. Start the application by using npm start command.
4. Seed the database using the following command. node ./tasks/seed.js
5. Once the server is up, we can request the path in browser. http://localhost:3000 which will take to initial page.

Access guide to the application.

1.If you are a new user please select sign up link in the initial page. 
2.You can select the option to sign in as either ride provider or ride seeker.
3.Enter personal information and car information if you have selected as ride provider. Enter only personal information if selected as ride seeker. All the fields are mandatory except apt.
4.Click the submit button to create a profile. email id is used as login id.
5.Click the Click here to sign in button to log in to the application.
6.Click on the Login button and enter your user credentials and captcha. Valid credentials will take you to main application.
7.In the Profile tab, you will be able to see your basic information. Below you will see your recent notifications.
8.To update the profile click on update profile button.
9.To delete the account click on delete account button.
10.If you are logged in as ride provider you will be able to click the rides provided, rides seeked and search a ride.
11.To provide a new ride click on rides provided and then click on to provide a ride-click here. you can view the list of your future travel plans. 
12.Fill up the information and click post a ride. If the ride is created successfully it will be listed in the travel plans.
13.You can update any ride by clicking update ride button on the particular ride.
14.You can delete any ride by clicking delete ride button on the particular ride.
15.To seek a ride click on Rides seeked and then click on seek a ride.
16.You can select the from city, destination city, travel time and then search for any rides.
17.When you click on search, it will result the travel plans created by others for the searching criteria.
18.You can book any travel plan by clicking book a ride, you can select the number of seats required.
19.Once the ride is booked successfully you can view the list of rides you are seeking.
20.To update a number of seats for any ride which is seeked, click on update button on the particular ride.
21.To delete a seeked ride, click on delete button on the particular ride.
22.If the user is signed up as ride seeker he will be able to all the above and except providing a ride.
23.To log out, click the log out button.

* If the user is already signed up, he can directly login into the system by providing valid credentials.
* The application tested using chrome browser. time field may not appear properly in mozilla. In that case the time format should be HH:MM (hours:minutes)


On successful db seed:
1. 4 members are created with 2 ride providers and 2 ride seekers.
2. The user credentials are Philip.Baressi@stevens.edu,mbabu@stevens.edu.svelan@stevens.edu and aprasad@stevens.edu. The password for all the account is test@1234.
3. Created 2 travel plans for Philip.Baressi@stevens.edu and one travel plan for mbabu@stevens.edu. travel date as 08/23/2016 from Hoboken to Brooklyn.

*Once the db seed is done, the above information can be tested in the applicaion and book any ride and view them in rides seeked. By default the db seed does not do any booking of ride.




