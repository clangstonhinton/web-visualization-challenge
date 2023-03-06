# web-visualizations-challenge
Used Python, HTLM, bootstraping and CSS to create a visualization dashboard website to house and render data analytics.

Here is a link to the website:  https://clangstonhinton.github.io/web-visualization-challenge/



## Latitude - Latitude Analysis Dashboard

The purpose of this analysis was to determine how weather changes as latitude nears the equator.
Data analysis was performed on a random sample of 500 cities across the globe to determine the relationship between latitude and various weather elements, including: temperature, humidity, cloudiness and wind speed. 

Scatter plots where graphed using Matplotlib to depict the relationships between latitude and the four weather elements. The site contains all the souce data and visualizations produced for the data analysis, with descriptions of any correlations observed.
 
The dashboard website contains 7 pages, as detailed below.

#### Landing Page
The landing page opens with an overview of the data analysis project on the left side and visualizations of all four plots on the right side of the page. The plot images also serve as navigation to each plot's detail page. This is a responsive page.

   <img width="872" alt="Screen Shot 2023-03-06 at 3 06 29 PM" src="https://user-images.githubusercontent.com/44728723/223219299-1fc83357-3825-4b50-9320-4c410b5c2ee9.png">
 
    
#### Four Visualization Pages
There are 4 visualization page - one page for each plot. Each visualization page provides details and observations about the plot and its significance. The page also contains the 4-box visualization container and provides a means to navigate between them the plots. This is a responsive page and when viewed on smaller screens, the visualization container moves beneath the detailed plot summary.
    

#### Comparison Page
The comparison page contains all of the visualizations on the same page for ease of visually comparison. This page sses a Bootstrap grid for the visualizations. The grid ia two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.
    
    
    
#### Data Page
The data page contains the detailed source data of the weather elements, latitude and longitude of each of the 500 cities  The data table is responsive and varies in size based on the screen size of the device rendering the page.



#### Navigation 
The navigation bar is at the top of every page. The "button" on the left of the navbar has the name of the site which allows users to return to the landing page from any page. The navbar contains a dropdown menu on the right side named "Plots" that provides a link to each individual visualization page. There are 3 more text links on the right side of the navbar: "Comparisons," which links to the comparisons page, "Data," which links to the data page, and "Repo", which links to the GitHub repository webpage. The navigation is responsive (using media queries) to smaller screens.


## References

OpenWeatherMap.org. (2012). Сurrent weather and forecast. Retrieved from [https://openweathermap.org/](https://openweathermap.org/)



