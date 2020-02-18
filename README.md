# project-gtd

Uploading here my very first data visualization, apologies for the coding as it is still very 'procedural'. 
When I did this I was still learning how to code properly in OOP structure. 

**Summary Content**
* Project: Global Terrorism Trends - Basic Data Visualization
* Geography: Worldwide
* Time period: 1970-2017, except 1993 (there were lots of missing data on year 1993 prior to the database compilation)
* Variables: DB contains 135 columns, but I only picked 14 variables containing dates, location, tactics, perpetrators, targets, and fatalities.

Steps to run on your local desktop: (using Bokeh Server)
1. Download the GTD csv file at https://www.kaggle.com/START-UMD/gtd
2. Download the gtd_app.ipynb. Ensure the file and module are in the same base dir.
3. Run the module via prompt, key in command: bokeh serve --show gtd_app.ipynb
4. An interactive dashboard hosted locally will be prompted.

This module still has LOTS to improve. I'm creating another version with Javascript callbacks so I can host the interactive 
visualization via web. Feedbacks are highly appreciated on this. Thanks very much for reading.

References: 
* https://www.kaggle.com/START-UMD/gtd
* https://www.start.umd.edu/gtd
* https://start.umd.edu/gtd/downloads/Codebook.pdf
