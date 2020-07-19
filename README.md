# Star Wars Fan Survey

## Summary

While waiting for [Star Wars: The Force Awakens](https://en.wikipedia.org/wiki/Star_Wars:_The_Force_Awakens) to come out, the team at [FiveThirtyEight](http://fivethirtyeight.com/) became interested in answering some questions about Star Wars fans. In particular, they wondered: __does the rest of America realize that “The Empire Strikes Back” is clearly the best of the bunch?__

The team needed to collect data addressing this question. To do this, they surveyed Star Wars fans using the online tool SurveyMonkey. They received 835 total responses, which you download from [their GitHub repository](https://github.com/fivethirtyeight/data/tree/master/star-wars-survey).

The data has several columns, including:

- `RespondentID` - An anonymized ID for the respondent (person taking the survey)
- `Gender` - The respondent's gender
- `Age` - The respondent's age
- `Household Income` - The respondent's income
- `Education` - The respondent's education level
- `Location (Census Region)` - The respondent's location
- `Have you seen any of the 6 films in the Star Wars franchise?` - Has a `Yes` or `No` response
- `Do you consider yourself to be a fan of the Star Wars film franchise?` - Has a `Yes` or `No` response

There are several other columns containing answers to questions about the Star Wars movies. For some questions, the respondent had to check one or more boxes. This type of data is difficult to represent in columnar format. As a result, this data set needs a lot of cleaning.


Tools Used-

Anaconda Jupyter Notebook
Pandas Lib
Matplotlib lib



Starwars guided project help taken from
david.vanheeswijk
https://nbviewer.jupyter.org/urls/community.dataquest.io/uploads/short-url/qFIYEus5UKHUNloe7qM0tMlbhIK.ipynb


nnabugwukelvin.chukw
https://nbviewer.jupyter.org/urls/community.dataquest.io/uploads/short-url/pNPS4apKR1D0M4nakMChbeaqRY2.ipynb

jafarinasim
https://github.com/nasimjafari7/PythonProjects/blob/master/Guided%20Project_%20Star%20Wars%20Survey/Basics.ipynb


ImerCardona
https://nbviewer.jupyter.org/urls/community.dataquest.io/uploads/short-url/k3VE6Gc7YCLybsBuFZocDi3AkTA.ipynb.

barGraph Design
https://scentellegher.github.io/visualization/2018/10/10/beautiful-bar-plots-matplotlib.html



# <span style='color:Green'>Conclusion Notes </span>

### Data has been analysed from multiple dimensions, from which we have to conclude below points
- Most Favorite Movie
    - `Star Wars: Episode V The Empire Strikes Back` is most favorite movie between different locations, age-groups and gender 
- Most Watch Movie
    - Locations - East North Central, Pacific, South Atlantic have shown highest interest in movie `Star Wars: Episode V The Empire Strikes Back` and `Star Wars: Episode VI Return of the Jedi`
    -  `Star Wars: Episode VI Return of the Jedi` is most watched movie after episode 5

- Least Like Movie
    - `Star Wars: Episode III Revenge of the Sith` is least favorite movie hence the least watched movie
