# Bikesharing
## Purpose
The purpose of this challenge was to use our knowledge of Python and Pandas to convert the "tripduration" column into a datetime format. Then, use our new skills with Tableau to create a bike trip analysis with the NYC CitiBike data.

In this analysis I will be pulling images from this link [link to dashboard](https://public.tableau.com/app/profile/christopher2993/viz/Bikesharing_16759158772570/Story1?publish=yes)

## Results
### Top Starting Locations
It was suggested early on that tourists were the reason for the large focus of bike use in the heart of the city. However, it shouldn't be overlooked that this area is also a large focus for commuter traffic.

![Top Starting Locations](https://user-images.githubusercontent.com/115501756/217718342-a9f40992-7a43-4ff7-811b-b5537e0b62e0.png)

### Peak Hours
The peak hours further suggests that the main user base consists of commuters. The first peak happens between 7am and 9am, while the second peaks occurs during rush hour at 5pm to 6pm.

![Peak Hours](https://user-images.githubusercontent.com/115501756/217718646-79a3392b-4333-405c-85d8-da8df8c2d5d5.png)

### Checkout Time for Users
Most users don't use the bikes for more than an hour. In fact, most are only using the bikes for 10-20 minutes. If we were to stick with the theory of a largely commuter based userbase, this 10-20 minutes would be approximately the amount of time it takes a person to commute to work on bike.

![Checkout Time for Users](https://user-images.githubusercontent.com/115501756/217719020-7aad8048-ab94-4403-9016-c37bee4e905a.png)

### Checkout Time by Gender
Seeing these same times, a large portion of it is done by men. This would support the idea of a largely male dominant working class within the city.

![Checkout Time by Gender](https://user-images.githubusercontent.com/115501756/217719223-ba68ff29-e8be-40b7-a9e2-1a3eae95f9a1.png)

### Trips by Weekday per Hour
This visual shows that most of the activity for the bikes is done during the weekdays, that being workdays. As we established in the "Peak Hours" visual, most of this activity during the week is also done during morning commute and rush hour. 

![Trips by Weekday per Hour](https://user-images.githubusercontent.com/115501756/217719510-5eb500f6-2a4b-4f3b-bebf-d6ca2ccd0ca4.png)

### Trips by Gender (Weekday per Hour)
This visual provides the same data for activity during the week, but divides it up by gender. Much like the "Checkout Time by Gender" visual, this one shows a larger male user base.

![Trips by Gender (Weekday per Hour)](https://user-images.githubusercontent.com/115501756/217719701-effa18f2-c559-43bf-b981-ad7632b1b4f4.png)

### User Trips by Gender by Weekday
This visual shows three things: The type of users, their genders, and the most popular times of use during the week. As seen in previous visuals, there is a dominant male userbase, mostly using the bikes during the workweek. What this visual provides us with is the fact that most of the userbase is also subscriber based. It is unlikely that "tourists" would subscribe to CitiBike.

![User Trips by Gender by Weekday](https://user-images.githubusercontent.com/115501756/217720159-8bd71a65-f051-4103-8b09-9a47e8e7af05.png)

## Summary
While it the idea was floated early on in the module that tourists could be a potential reason for such high usage of CitiBike in the city, there is more evidence supporting the theory that the userbase is made up of commuters heading to and from work during the week. The "Peak Hours" and "Trips by Weekday per Hour" visuals both show that the highest usage of the bikes occurs during morning commute (7a-9a) and rush hour (5p-6p). On top of this, the "Top Starting Locations" visual shows a large amount of activity in the heart of the city, mainly on major commuter roads. 
If investors needed more data, I would suggest:
1. Start and End locations at different hours of the day to find a possible correlation between users coming in and out of the city and the morning commute and rush hours.
2. Something regarding the age of the users, to see the difference between those of working age and those retired.
