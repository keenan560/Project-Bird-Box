# Team Synergy

Team Project 1

Giselle Malenchek

Keenan Mapp

Austin Taranto 


Our Team built an application titled Bird Box.

# Purpose:

When it comes to choosing a place to live there are many factors to consider. For example, how safe is it? What's the crime rate? Am I going to find some level of employment? What are the home prices in the area? These and many more topics are caveats that each play a part in the whole process of finding our niche.

Hence our team decided to tackle just a few of those many factors by researching and connecting with a few APIs to answer these questions.

# APIs 

- FBI Crime Data Explorer
- USA Jobs Data
- College Scoreboard
- Firebase


# Front End

When the User comes to the website they will share some valuable data points such as:
    - Age
    - Desired State to live
    - Marital Status
    - Number of Children (if any)
    - Desired Job Title
    - Current Job Status

Once the User enters their data and clicks the Search button, the application will then render results to the browser based on their input. 

# Back End

When the Search button is clicked, our javascript code saves each data input as variables and creates an object with those variables. This object is then pushed to the firebase database for this application in real time for storage, thus capturing every search.

Next our code makes calls using AJAX to the APIs listed above. When the response is received we then create new elements containing results that append to the page.


# Future

We would like to take all the variable and create a formula which will take the data and decide whether or not the User's choice is good place to live. For example, the crime rate is too high, not enough colleges, lack of jobs etc.

We are currently looking for a Real Estate API in order to return home prices by city and or state. Since the jobs API that we connect to is only US Govt. jobs, we would like to connect to one that also includes Private Sector jobs. 



# Technolgies

- Boostrap
- jQuery
- HTML
- CSS
- Javascript

Try it out!

Bird Box Website: https://keenan560.github.io/Project-Bird-Box/


