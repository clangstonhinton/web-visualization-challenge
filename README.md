# web-visualizations-challenge
Used Python, HTLM, bootstraping, CSS, and MatPlotLib to create a visualization dashboard website to house and render data analytics.

Here is a link to the website:  https://clangstonhinton.github.io/web-visualization-challenge/



## Latitude - Latitude Analysis Dashboard

The purpose of this analysis was to determine how weather changes as latitude nears the equator.
Data analysis was performed on a random sample of 500 cities across the globe to determine the relationship between latitude and various weather elements, including: temperature, humidity, cloudiness and wind speed. 

Scatter plots where graphed using Matplotlib to depict the relationships between latitude and the four weather elements. The site contains all the souce data and visualizations produced for the data analysis, with descriptions of any correlations observed.
 
The dashboard website contains 7 pages, as detailed below.

#### Landing Page
The landing page opens with an overview of the data analysis project on the left side and visualizations of all four plots on the right side of the page. The plot images also serve as navigation to each plot's detail page. This is a responsive page and displays the content vertically on small screens.

<p align="center">
 <img width="618" alt="Screen Shot 2023-03-06 at 3 10 28 PM" src="https://user-images.githubusercontent.com/44728723/223219892-84d6d87d-bd15-4323-9960-de509dd80ce5.png">
     
#### Four Visualization Pages
There are 4 visualization pages - one page for each plot. Each visualization page provides details and observations about the plot and its significance. The page also contains the 4-box visualization container and provides a means to navigate between the plots. This is a responsive page and when viewed on smaller screens, the visualization container moves beneath the detailed plot summary.

 <p align="center">
  <img width="710" alt="Screen Shot 2023-03-06 at 3 17 20 PM" src="https://user-images.githubusercontent.com/44728723/223221185-2f69c55e-cc08-48e5-b802-473ca81ec25d.png">

#### Comparison Page
The comparison page contains all of the visualizations on the same page for ease of visual comparison. This page uses a Bootstrap grid for the visualizations. The grid holds two visualizations across on screens medium and larger, and 1 across on small screens.
    
<p align="center">
 <img width="622" alt="Screen Shot 2023-03-06 at 3 20 25 PM" src="https://user-images.githubusercontent.com/44728723/223221735-08fbc2b8-7b9e-4e09-9c0f-0190b1033bc5.png">
    
#### Data Page
The data page contains the detailed source data of the weather elements, latitude and longitude of each of the 546 cities  The data table is responsive and varies in size based on the screen size of the device rendering the page.

<p align="center">
 <img width="621" alt="Screen Shot 2023-03-06 at 3 22 34 PM" src="https://user-images.githubusercontent.com/44728723/223222139-17f811c0-d72b-445b-9a98-d335b788e480.png">

#### Navigation 
The navigation bar is at the top of every page. The "toggle" text box on the left of the navbar has the name of the site which allows users to return to the landing page from any other page. The navbar contains a dropdown menu on the right side named "Plots" that provides a link to each individual visualization page. There are 3 more text links on the right side of the navbar: "Comparisons," which links to the comparisons page, "Data," which links to the data page, and "Repo", which links to the GitHub repository webpage. The navigation is responsive (using media queries) to smaller screens.


## References

OpenWeatherMap.org. (2012). Сurrent weather and forecast. Retrieved from [https://openweathermap.org/](https://openweathermap.org/)



