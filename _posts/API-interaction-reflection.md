Interacting with API’s reflection 
================
Brennan Clinch
10/4/2021


I have completed a project on working with API’s to query data that you
want. The link to the project is
[here](https://brennan-clinch.github.io/Project_1/) and the link to the
repository is [here](https://github.com/Brennan-Clinch/Project_1).

\#The Project

For this project, I created a vingette that gives us information on ways
we can interact with API’s through the use of functions we create that
can query things we want and return them in a nice fashion. I used an
API for COVID-19 data. I then created several functions that would
interact with the COVID-19 API and then return queried data on COVID-19.
After creating the functions, I then used some of them to do data
analysis on COVID-19. Some interesting trends I found were that
Confirmed Cases and Deaths had a positive relationship and the fact that
in Canada, which is the country north of the United States, that Spring
of 2021 was when COVID-19 reached it’s highest amount of cases
(Specifically in April).

\#My Reflections

Overall, most of the project went smoothly with the data analysis and
the creation of some of the API functions. However, the setup and some
of the logic for some of the functions was confusing since I had to use
“all” in my function and it was confusing to understand what the
function was actually doing and what part of the data it was referring
to when selecting what thing I want the object inside my function
returning. Since I hadn’t had a lot of experience with querying with
API’s before now and this was my first time doing this it took a lot
more time than needed just to figure out how to use conditional logic
with subsetting the data.

It was also tricky to create some of the functions to be able to return
certain results from COVID since most of the endpoints use a slightly
different abbreviation for the Countries I am interested in querying for
the COVID-19 API endpoints so it required me to be able to look at the
original dataframe more often just to check the abbreviation or slug for
countries.

The last thing that was difficult and annoying with regards to the
programming was that for COVID data, they only gave the total data and
not daily case data for both of the functions I used in my data
analysis, so I had to use loops/conditional logic to be able to change
the cases/deaths/etc to be daily instead of total.

For what I would do differently next time I would do a project like this
would be that I would most likely see if there are any more resources or
sample projects for doing what I did for this project along with asking
for more opinions on what areas are the most important to query that
others would be interested in, since for COVID data I just went with
what I thought was important which was the confirmed cases.
