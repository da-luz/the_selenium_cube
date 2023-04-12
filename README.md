# **_The Selenium Cube_**
___

## Project Synopsis:
This project is a **Rubik's Cube Speedsolving** data pipeline in order for it to be used on further analysis (Coming Soon).

### The case:
In _The Statistical Cube[link](https://github.com/da-luz/the_statistical_cube)_ we saw an atempt to define and run a model for predicting upcoming Speedsolving Records. That data was scrapped from the official _WCA_ (World Cubing Association) website like neanderthals did scrapping in those times: by visiting each page and pasting data on Excel's sheets.

For the sake of model veracity - how good is it's picture from reality - and their usability for other kinds of analysis, we must gather more data; which, sometimes, is Sisyphus Work (meaning a laborous task).

### The solution:
If we, humans, do not want to do something, then give the task to a robot!

This code is a browser automation using Selenium, it shall run through all WCA competitions pages (since 2009) and get the data that we need.

## What this code do until now?
See, it is not an easy task even for computers. So it is a work in progress. Now, the only thing that this code do, is scan the _Past Competitions_ page retriving the **Name** of event, its **Page URL** and a class from the HTML that shows the **Country** in which country occurred the contest

## What this code will, eventually, do?
- [x] Gather competitions names, urls and country
- [ ] Retrieve solving data from each competitions page
- [ ] Save it to a .csv file
- [ ] Do some statistics babble analysis