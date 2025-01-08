# Project Description: Microbial Community Analysis for Forensic Identification
This project involved analyzing data from a bioinformatics study that explored the use of skin-associated microbial communities for forensic identification. The study focused on linking individuals to objects they interacted with based on the microbial signatures they left behind.

Tools and Programming Languages:
Python:
Data processing with pandas and visualization with matplotlib and seaborn.
Dimensionality reduction using PCA (sklearn) and statistical analysis.
Distance computation using metrics such as Bray-Curtis.
Bioinformatics Libraries:
Utilized scikit-bio for dimensionality reduction and working with distance matrices.
Workflow:
Data Cleaning and Processing:

Filtered the dataset to focus on relevant experiments.
Enriched the metadata by adding columns based on automated processing.
PCA Analysis:

Performed dimensionality reduction to retain the most significant variation in the data.
Calculated the contribution of each principal component to the dataset's variance and visualized the results.
Visualization and Insights:

Created color-coded plots to distinguish between different sample types.
Generated heatmaps to illustrate similarities between samples.
Compared multiple distance metrics and evaluated their impact on data separation quality.
Key Findings:
The developed code successfully highlighted differences between microbial samples from individuals and objects, demonstrating potential for forensic applications.
The tools and techniques used in the project provide a solid foundation for further research in the field.
