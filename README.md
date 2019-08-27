# HW09_Web_VZ_DB
9: HTML and CSS Homework | Assignment - Web Visualization Dashboard (Latitude)

## Files
* [Data](https://github.com/DanielMJones2005/HW09_Web_VZ_DB/tree/master/Data)
    * cities.csv
 
* [Dev_Files](https://github.com/DanielMJones2005/HW09_Web_VZ_DB/tree/master/Dev_Files)
    * various files for development
 
* [Img](https://github.com/DanielMJones2005/HW09_Web_VZ_DB/tree/master/Img)
    * Relevant image files:
    * lat_vs_cloud.png
    * lat_vs_hum.png
    * lat_vs_maxtemp.png
    * lat_vs_ws.png

  
* [.gitignore](https://github.com/DanielMJones2005/HW09_Web_VZ_DB/blob/master/.gitignore)
* [HW09_WebViz_Data.v1.ipynb](https://github.com/DanielMJones2005/HW09_Web_VZ_DB/blob/master/HW09_WebViz_Data.v1.ipynb)
* [cities.html](https://github.com/DanielMJones2005/HW09_Web_VZ_DB/blob/master/cities.html)
* [index.HTML](https://github.com/DanielMJones2005/HW09_Web_VZ_DB/blob/master/index.HTML)
* [style.css](https://github.com/DanielMJones2005/HW09_Web_VZ_DB/blob/master/style.css)

## Background
 - Data is more powerful when it is shared with others! Use HTML and CSS to create a dashboard showing off 
 an analysis.

## Latitude - Latitude Analysis Dashboard with Attitude
- Create a visualization dashboard website using visualizations created in a past assignment. Specifically, 
  plotting weather data.
  
- In building this dashboard, create individual pages for each plot and a means by which one can navigate between them. 
  These pages will contain the visualizations and their corresponding explanations. 
- Pages:
    - Have a landing page
    - A page where one can see a comparison of all of the plots
    - and another page where one can view the data used to build them.
  
## Website Requirements
- The website must consist of 7 pages total, including:

   - A landing page containing:
        - An explanation of the project.
        - Links to each visualizations page.

   - Four visualization pages, each with:
        - A descriptive title and heading tag.
        - The plot/visualization itself for the selected comparison.
        - A paragraph describing the plot and its significance.

   - A "Comparisons" page that:
        - Contains all of the visualizations on the same page so we can easily visually compare them.
        - Uses a bootstrap grid for the visualizations.
        - The grid must be two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.

   - A "Data" page that:
        - Displays a responsive table containing the data used in the visualizations.
        - The table must be a bootstrap table component.
        - The data must come from exporting the .csv file as HTML, or converting it to HTML. 
  
- The website must, at the top of every page, have a navigation menu that:
   - Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
   - Contains a dropdown on the right of the navbar named "Plots" which provides links to each individual visualization page.
   - Provides two more links on the right: "Comparisons" which links to the comparisons page, and "Data" which links to the data page.
   - Is responsive (using media queries). 


- Finally, the website must be deployed to GitHub pages.
   - https://danielmjones2005.github.io/HW_09/
        - best viewed in Google Chrome
    

