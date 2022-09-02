# UFO Analysis with JavaScript

## Project Overview
The goal of this challenge is to provide a more in-depth analysis of UFO sightings by allowing users to filter through the data for specific criteria. The filter includes date, city, state, country and shape. The webpage does not have a "button", instead the page will automatically update with regards to the search criteria when the user inputs it. 

## Resources
-   VS Code 1.70.2
-   HTML5, Bootstrap 4.6.1
-   JavaScript

## Results
### Website Layout
![Website_Image](https://github.com/nfujikad/UFOs/blob/main/Resources/Website_Image.png)

-	The very top part is a navigation bar with text “UFO Sightings”.
-	Right below vav bar is a jumbotron written “The Truth Is Out There” with an image background.
-	Next section has two parts of content: left section has a header “UFO Sightings: Fact of Fancy?” and a sub-header “Ufologists Weigh In”; right section contains a paragraph of information.
-	The bottom left section is the filter input form, where users can input one or multiple filters by date, city, state, country and shape.
-	The bottom right section is the data table, which updates with filter inputs.

### User

-	In Filter Search section, input desired date，the table will update to results by that specific date.
  
    ![Search_Input](https://github.com/nfujikad/UFOs/blob/main/Resources/Search_Input.png)

-	OR, enter any other one or any multiple filters, press Enter, the data table will update to filtered data.

-	Click top of the page “UFO Sightings” in nav bar to reset the filter form and data table.
  
    ![Refresh](https://github.com/nfujikad/UFOs/blob/main/Resources/Refresh.png)


## Summary

### Drawback
The main issue with the website and search engine is the user needs to have knowledge of the data before conducting a search. For example, the user must know the available dates, cities, states, countries, and shapes in the dataset in order to get data returned. If the users randomly type a city that she/he wants to search for and it is not included in the data, nothing will return. 

### Recommendations
-	The drawback can be resolved by incorporating a drop-down menu/list for each filter. Therefore, the users will know available elements within each filter to avoid typing invalid input. 
-	It would be a more optimal user experience if there is a button at the bottom of Filter Search Section to confirm the search action, or to prevent premature searching/ loss of the current page.


