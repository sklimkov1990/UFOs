# UFOs

## Module Project Overview

We are creating a webpage for Dana that has a dynamic table, which is filtered using the date fieldwhich provides a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. Following filters are used on the table date, city, state, country, and shape.

## Resources:
  - Data Source: data.js
  - Software: JavaScript, HTML, CSS
  - Library: bootstrap 4.0.0, d3 4.11.0

## Module Project Analysis

  We can use date filter as follows to filter table data.

  - webpage:
  
    !["module webpage"](./static/images/module_webpage.png "module webpage")

  - filter:
    Enter date into the date filter textbox as shown 
    
    !["module webpage filter"](./static/images/module_webpage_filter.png "module webpage filter")
  
  - filtered table:
    Click on the button to filter the table data
    
    !["module webpage filtered data"](./static/images/module_webpage_filtered_data.png "module webpage filtered data")
  

## Challenge Overview

We are enhancing the webpage we already created for Dana by adding additional filters, which provides a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. Following filters are used on the table date, city, state, country, and shape.

## Challenge Analysis

  We can use the multiple filters to filter data as shown below
  
  - challenge webpage:
  
  !["challenge webpage"](./static/images/challenge_webpage.png "challenge webpage")
  
  - date filter:
    Enter date into the date filter textbox as shown and the table data is filtered right away
  
  !["date filter"](./static/images/challenge_webpage_filter_date.png "date filter")
  
  - city and state filter:
    Enter city and state as shown and data is filtered further
  
  !["city state filter"](./static/images/challenge_webpage_filter_city.png "city state filter")
  
  - state and country filter:
    Enter state and country to filter data
  
  !["state country filter"](./static/images/challenge_webpage_filter_state.png "state country filter")
  
  - shape filter:
    Enter shape to filter data even further
  
  !["shape filter"](./static/images/challenge_webpage_filter_shape.png "shape filter")
  
  - Reset filters:
    Reset filters by clicking on 'UFO Sightings' nav-bar up on top left.
  
  !["Reset"](./static/images/challenge_webpage_clear.png "reset filters")
  

### Summary

Based on the search criteria data displayed on the table changes dynamically.

#### Drawback of this webpage
The main drawback on this page is searching, we can only search on a whole match of the text entered and is in lowercase. We cannot search on a partial match or mixed case text entry.

#### Additional recommendations for further development

  Drawbacks are the recommendations for future development
  - Add Partial text search using string includes() function as opposed to '===' or '==' operators.
  - Add mixed case search by converting the text to all lowercase or uppercase.