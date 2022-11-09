# Belly-button-challenge
In this project we will build an interactive dashboard to explore the Belly Button Biodiversity dataset, which catalogs the microbes that colonize human navels.


![image](https://user-images.githubusercontent.com/106934375/193156876-9fe0e763-4eea-40e2-99bb-d74b96d009f1.png)

## Instructions
Complete the following steps:

## 1.Use the D3 library to read in samples.json 

Use the D3 library to read in samples.json from the URL https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.1/14-Interactive-Web-Visualizations/02-Homework/samples.json.

## 2.Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.

. Use sample_values as the values for the bar chart.

. Use otu_ids as the labels for the bar chart.

. Use otu_labels as the hovertext for the chart.
![image](https://user-images.githubusercontent.com/106934375/193156355-cf4e936e-bb63-44e0-91d8-f5e053f5f5ff.png)

## 3. Create a bubble chart that displays each sample.

. Use otu_ids for the x values.

. Use sample_values for the y values.

. Use sample_values for the marker size.

. Use otu_ids for the marker colors.

. Use otu_labels for the text values.

### Bubble Chart
![image](https://user-images.githubusercontent.com/106934375/193156428-4f36a28c-6fc4-4e35-84d7-33decd87fc99.png)


4. Display the sample metadata, i.e., an individual's demographic information.

5. Display each key-value pair from the metadata JSON object somewhere on the page.

![image](https://user-images.githubusercontent.com/106934375/193156453-4b1b9988-9067-41d0-9953-296aefb2b917.png)


6. Update all the plots when a new sample is selected. Additionally, you are welcome to create any layout that you would like for your dashboard. An example dashboard is shown as follows:
![image](https://user-images.githubusercontent.com/106934375/193156494-009570a5-b03f-4a37-b577-a66551d55c00.png)


Deploy your app to a free static page hosting service, such as GitHub Pages. Submit the links to your deployment and your GitHub repo. Ensure that your repository has regular commits and a thorough README.md file
