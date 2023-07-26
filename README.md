# Meteorite Landings Data Analysis

## Introduction
Meteorites are fascinating objects that have captivated the imaginations of people for centuries. These extraterrestrial objects provide a wealth of information about the origins and evolution of our solar system. This project aims to analyze various parameters associated with meteorite landings using a dataset maintained by NASA. The dataset contains information on the name, ID, geolocation, latitude, longitude, class, mass, fell/found, name type, and year of each meteorite.

## Dataset
The dataset used for this analysis is named 'Meteorite_Landings.csv'. It is a comprehensive collection of data on meteorites found on Earth, containing 10 columns and 45,715 rows. The dataset has been imported and analyzed using Python and various libraries, including pandas, numpy, matplotlib, seaborn, and plotly.

## Insights and Visualizations
The data analysis covers various aspects of meteorite landings, including:

Handling Missing Values: Missing values in the 'mass (g)', 'year', 'reclat', and 'reclong' columns were handled by replacing them with the median value of the respective columns.

Number of Meteorites Before and After the 21st Century: The total number of meteorites found before and after the 21st century was calculated and visualized using a bar chart and a line chart.

Most Prevalent Classes of Meteorites: The top 5 classes of meteorites were identified and visualized using pie charts. A function was used to group similar recclass types.

Frequency Distribution of Meteorite Masses: A histogram was created to show the distribution of meteorite masses.

Box Plots of Top Meteorite Classes by First Letter: Box plots were used to compare the total mass and mean mass of the top 5 meteorite classes, grouped by their first letter.

Scatter Plot of Total Classes of Meteorites Found vs Latitude: A scatter plot was created to show the relationship between latitude and the total classes of meteorites found.

Heat Map of Meteorites Found on the Globe: An interactive map was generated using plotly express to visualize the locations of meteorite landings on Earth between 1970 and 2015. The map also shows the equator and the percentage of meteorites above, below, and on the equator.

## How to Use
To reproduce the analysis and visualizations, follow these steps:

Download the 'Meteorite_Landings.csv' dataset and place it in the project directory.

Install the required libraries, if you haven't already:

bash
>pip install pandas numpy matplotlib seaborn plotly

1. Open the Jupyter Notebook (or your preferred Python environment) and run the code cells in the 'meteorite_landings_analysis.ipynb' notebook.

2. The code will perform the data analysis and generate visualizations, which will be displayed in the notebook.

## Contributors
This project was carried out by Vivek Pani, Hemanth Kella, Ashish Yadav and Kannupriya. Contributions and feedback are welcome!

## License
This project is licensed under the UT Dallas License.

## Acknowledgments
Special thanks to NASA for providing the Meteorite Landings dataset, and to the developers of the Python libraries used in this analysis.

Feel free to customize the README file with additional information, links, and relevant images. Also, make sure to include the appropriate license file (e.g., LICENSE) in your project directory.
