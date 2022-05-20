## Inspiration

Since most travel apps do not sort travel destinations by preferred temperature and precipitation levels, we decided that we could make a website that would fill this niche and offer people travel destinations based on their weather preferences as well. This led to the creation of The Weathered Traveller, a web application that uses climate data involving precipitation and temperature to calibrate the best travel destination. 

## What it does 

The Weathered Traveller is a site that allows the user to select the ideal travel destination based on their preferences for the climate of the area. The user inputs their preferences for precipitation and temperature, and the site then searches through a database of climate data to find the closest match that best fits their request and prints out the city name.

## How we built it 

In terms of our tech stack, it was a combination of familiar languages and also explorative technologies. For the frontend, we used HTML, CSS, and JS for our landing page, and used Heroku for the backend. The backend was connected to the front end via a form, and the data from OpenWeather’s data sets were filled into a Google Sheet. It was then propagated into Heroku’s system and sorted based on temperature or rainfall data. After that, the information was relayed back to the front end using AJAX and python requests to display the final result in terms of what the best match for the user was. To get the data, we used the OpenWeatherMap API, the radar.io location API, and a web scraper with python’s beautifulsoup and scrapy. 

## Challenges we ran into
The front-end developers, all of whom were first-time hackers, encountered many challenges with creating their first working website from scratch. This included creating many widgets and the overall layout of the website from scratch. There were also some difficulties making sure that the website would display properly in mobile devices as well as laptops, and there were often conflicting CSS rules that led to unexpected results. On top of this, there were many other bits of frontend code, including fancy sliders and drop-down menus, and multiple other web pages that never made it into the final product since much of the frontend code was not compatible with the backend functionality. There was a fair share of things that went wrong in the backend too. We had trouble scaling the dynos and the procfile for Heroku, and we had to learn gspread from scratch. 

## Accomplishments that we’re proud of

Knowing full well that there are plenty of people who attend hackathons and end up with a non-functioning application, being able to actually make something as extensive as our application work was a major achievement. We felt even better about this given the fact that half our group was completely new to hackathons. This hackathon was the first time the majority of us had interacted with anything web-related (HTML/CSS), and we worked really hard to understand the basics of how hackathons functioned and worked. Most importantly of all, we learned how to use API from the web as the foundation of our project, and how different aspects of front and back end can receive data from one another to create an innovative hack!

## What we learned 

Regarding the frontend aspect of our project, we learned many new things. For most of us, we learned firsthand how hackathons operate, and how we can tailor a specific project to one using the fundamentals of web design, HTML, and CSS. This included how to create customizable sliders that could hold one or two values, resizing web pages based on what device the user is using, and how to connect the frontend to the back end. We also learned how to convert between multiple different file types, and using the multiple APIs. For backend, we learned how to use a multitude of APIs without resorting to git bash which was an achievement, as well as learning how we can convert between multiple file types like JSON and CSV. Overall, we had an amazing experience, and plan on attending more hackathons in the future. 

## What's next for The Weathering Traveller

As a result of the short deadline, there were many features that we simply did not have enough time to add. One feature that would improve the site is to offer multiple options for cities that meet the temperature and precipitation criteria. Another would be sorting by COVID-19 data to be aware of the safety risks when traveling rather than being driven by the sightseeing aspect. We could also display the locations as markers on an embedded google map for ease of access. We are looking forward to adding more information to search results, such as displaying links to tourism sites and short descriptions. We could also add back some of the frontend features that we dropped because of a lack of time. Instead of text boxes to act as input for the application, we could have used sliders and dropdown menus. We could have also improved the visual aspect of our site more and added more features to sort tourist destinations.
