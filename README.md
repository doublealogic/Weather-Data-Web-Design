# Web Design Challenge

## Background
This repository took everything I learned about HTML and CSS to create a dashboard website visualizing the work I did on a previous repository, `https://github.com/doublealogic/api-challenge-python`. In that repository, I used  citipy, a simple Python library, and the OpenWeatherMap API, to create a representative model of weather across 500+ world cities, which were of varying distance from the Equator.

### Folders Overview
The `assets` folder contains pictures of ten cities that were generated from my temperature search of the 500+ cities.

Within the `Resources` folder, is the csv created out of the above search and holds the data for the above cities.

Last, the `visualizations` folder holds graphs that displayed relationships between various weather aspects and latitude.

### Website Requirements
Below were the website requirements that I needed:

The website must consist of 7 pages total, including:

* A `landing page` containing:
  * An explanation of the project.
  * Links to each visualizations page. It would have a sidebar containing preview images of each plot, and clicking an image would take the user to that visualization.
![Landing Page](assets/Front_Page_Preview.png)

* Four `visualization pages`, each with:
  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.
![Temp Visualization Page](assets/Plot_Page_Preview.png)

* A `"Comparisons" page` that:
  * Contains all of the visualizations on the same page so one could easily visually compare them.
  * Uses a Bootstrap grid for the visualizations.
    * The grid must be two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.
![Comparisons Page](assets/Comparisons_Page_Preview.png)

* A `"Data" page` that:
  * Displays a responsive table that would contain the data used in my visualizations.
    * The table needed to be a bootstrap table component.
    * The data had to come from exporting my `.csv` file as HTML, or converting it to HTML.
![Data Page](./assets/Data_Chart_Preview.gif)

The website must, at the top of every page, have a navigation menu that:

* Has the name of the site on the left of the nav which would allow users to return to the landing page from any page.
* Contains a dropdown menu on the right of the navbar named `"Plots"` that provides a link to each individual visualization page.
* Provides two more text links on the right: `"Comparisons,"` which links to the comparisons page, and `"Data,"` which links to the data page.
* Is responsive (using media queries).

Finally, the website had to be deployed to GitHub pages.

### Additional Considerations

I took some liberty in the visual aspects of the websites by using the Bootstrap Theme Lux from Bootswatch.