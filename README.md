# Github-issues-App

this is for displaying the issues which are open for a given public github repository
the app catogorizes it as the issues which are open for one day,more than one day but less than a week , more than one week and 
remaining.
IT also displays top 10 latest issues for the repository
how it works is very simple
it makes a call to the GitHub api and fetches data in json format
the data so obtained contains various fields like url,id date of creation etc
since we are concerned for the time we have to just take the value of  time feild for each issue and compare it with current date 
There are several variables which are used for each type of category like count of issues opened for a day
count of issues opened for a week
and remainig issues which are opened for more than a week

The programming for the app is done by javascript

the UI of the app is basic UI made using HTML,Jquery and CSS

if more time given we can add extra feautures in the app like pagination,comment box for each issues
profile link of the user who raised the issues etc
