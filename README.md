# GEOG5990M project final assignmnt

# Project Background
This project focuses on the spatial distribution of e-commerce access in Leeds, United Kingdom. In today’s digital age, understanding the disparities in access to e-commerce can provide valuable insights for policy-makers, businesses, and community leaders. The analysis aims to identify areas with varying levels of e-commerce access and understand how these levels correlate with different demographic and socio-economic groups classified by output areas.

# Project Objectives

Merge multiple datasets including demographic data, socioeconomic indexes, and geographical data pertaining to Leeds.

Analyze the e-commerce access across different output areas classified within the city.

Visualize the results using both statistical graphs and geographical mapping to provide a comprehensive view of the data.

# How the Code Works
1. Data Loading and Preparation:

   NSP21CL_NOV23_UK_LU_1.csv: National statistics postcodes data.

   ppfi_index_v2_nov2023.csv: Postcode level Future Internet Index data.

   oac21ew.csv: Output Area Classification data.

   classification_codes_and_names.csv: Descriptive names for each classification code.

   A shapefile containing the geographical boundaries of Leeds.

3. Data Filtering:
The data from NSP21CL_NOV23_UK_LU_1.csv is filtered to only include entries from Leeds using the 'ladnm' field.

4. Data Merging:
The datasets are merged based on geographic codes to associate internet access indexes with output area classifications and geographic boundaries.

5. Data Analysis:
The merged data is then used to compute the distribution of e-commerce access index across various demographic groups within Leeds.

7. Visualization:
A bar plot is generated to visually represent e-commerce access by different output area classifications.
A geographical map is produced to show the spatial distribution of e-commerce access in Leeds. The map uses a 'coolwarm' color scheme to depict varying levels of access, with the color intensity representing the priority of access from highest to lowest.

8. Visualization Outcomes:

    Bar Chart: Demonstrates the e-commerce access index for different classifications, highlighting significant disparities between areas.
   
    Geographical Map: Provides a spatial representation of e-commerce access, showing how access is distributed across Leeds. The color-coded map helps identify high-priority and low-priority areas in terms of e-commerce access.

# Usage
To use this code:

1.Clone the repository.

2.Ensure you have the required Python environment and packages installed.

3.If you are using Colab, make sure all the data have uploaded to /content.

3.Run the script to generate the visualizations and analyze the data.

# Conclusion
The analysis helps in understanding the urban digital divide in Leeds and can guide efforts to improve digital inclusivity across the city. By visualizing the data, stakeholders can more easily interpret patterns and make informed decisions.

This repository provides all necessary scripts and instructions to replicate the study, fostering transparency and encouraging further research in this vital area.
