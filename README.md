# UFOs
Module 11: Using Javascript

## Overview of Project:
### Helping Dana to improve her website.  

- Background
"Dana’s webpage and dynamic table are working as intended, but she’d like to provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. In addition to the date, you’ll add table filters for the city, state, country, and shape."

In order to help Dana improve her webpage and the user interface additional search fields were added.  Using E6+, HTML, Bootstrap, and JavaScript as the primary coding language I was able to create a smoother user experience.  Now a user can search for date, city, state, country, or shape to help view the data submitted.  

![module_site_png](https://github.com/GrahamNeal13/UFOs/blob/main/read_me_img/module_site.png)

## Results:
### Improved site with filters.

After editing the site to include the additonal search fields a user can now input any of the five elements to filter the database that has been collected.  

![challenge_site.png](https://github.com/GrahamNeal13/UFOs/blob/main/read_me_img/challenge_site.png)

This will also allow a user to use multiple fields to narrow down their search to find a specific report or common experiences.  For example if a user were to search by "state" and "shape" they would be able to see that there was 11 reports in the state of California of light.  
The site will also log the searches in the console of the webpage so that Dana can review the most common searches to help in future refining of data and her webpage.  

![filtered_console.png](https://github.com/GrahamNeal13/UFOs/blob/main/read_me_img/filtered_console.png)

## Summary:
### What can be learned.

Unfortunately this is not a perfect webpage, the main drawback issue is that the search fields are case sensitive.  If a user chooses to use capital letters when entering a search for "CO" it will result in an empty data table which we know to be false.  The place holders do show examples for the user to replicate but not every person using the site may relieve this tiny detail.  

![search_error.png](https://github.com/GrahamNeal13/UFOs/blob/main/read_me_img/search_error.png)

In order to fix this issue I would recommend using drop down selection options for the fields.  Since this is a finite dataset there are many common selections that can be used to filter the reports.  I would suggest possibly editing the comments as there are lots of symbols and spelling mistakes that would make trying to search the comments section quite difficult.  The page itself could also be made more device friendly by changing the search field layout and instead of having them on the side make them fixed above the data table.  Another recommendation would be to add a counter for the results so if the database is increased the user would be able to see how many results there are per search.  This would allow a user to see which state has the most reports.  
