# Unveiling Trends in Ford GoBike Trip Data

![Ford GoBike](./image/Ford_GoBikes.jpg)

Link blog: [Link Blog](https://github.com/dibang99/data_scientist_project/blob/main/blog_post.md)

## Domain Background

Ford GoBike is a bicycle-sharing service operating in the San Francisco Bay Area, offering residents and visitors a sustainable transportation option. The system allows users to rent bikes for short-term use, providing an eco-friendly alternative to traditional transportation methods. The dataset we’re examining includes detailed trip information such as duration, start and end times, stations, and user demographics.

## Problem Statement

With the wealth of data available from the Ford GoBike system, several key questions arise:

1. **How are trip durations distributed among users?**
   Understanding the duration of bike trips helps in assessing user behavior and system performance.
   
2. **What is the distribution of user types in the GoBike sharing system?**
   Identifying the proportion of different user types—subscribers versus customers—can shed light on user engagement and retention strategies.
   
3. **How does bike ride usage vary across different age groups?**
   Knowing which age groups are most active can assist in tailoring services and marketing efforts to different demographics.

## Dataset

The data collect from Kaggle. You can access the dataset and more details [Ford GoBike System Data](https://www.kaggle.com/datasets/ahmedmohameddawoud/ford-gobike-system-data)

## Solution Statement

To address these questions, we analyzed the Ford GoBike dataset and visualized the results

### Libraries used

- **pandas**: For data manipulation and analysis.
- **matplotlib**: For creating static, animated, and interactive visualizations in Python.
- **numpy**: For numerical operations and handling arrays.
- **seaborn**: For statistical data visualization.
- **folium**: For interactive maps.
- **sklearn.preprocessing.LabelEncoder**: For encoding categorical variables into numeric labels.

### Files in the Repository

- `data/201902-fordgobike-tripdata.csv`: The main dataset containing trip data from the GoBike system.
- `writing_data_scientist_blog.ipynb`: Jupyter Notebook containing the analysis, visualizations, and insights derived from the dataset.
- `image`: Directory containing visualizations such as histograms, pie charts, and heatmaps.
- `README.md`: This file, providing an overview of the project, libraries used, and file descriptions.
- `blog_post.md`: This file is blog of project

### Summary of Results

1. **Trip Duration Distribution**:
   - The histogram of trip durations shows that most trips are relatively short, with a long tail extending towards longer durations. This indicates that the majority of bike rides are quick, but there are also a significant number of longer rides.

2. **User Type Distribution**:
   - The pie chart reveals that subscribers significantly outnumber customers, with subscribers being nearly nine times more common. This suggests a high level of engagement among regular users.

3. **Age Group Usage**:
   - The bar plot indicates which age groups are most active in using the bike-sharing service. The plot helps in understanding the distribution of bike usage across different age ranges.

4. **Correlation Insights**:
   - The heatmap shows a very weak positive correlation between ride duration and user age, and no significant correlation between ride duration and the latitude of the starting station. This suggests that age and starting station location have minimal impact on ride duration.

## Acknowledgements

The dataset used in this analysis was collected from Kaggle. You can access the dataset and more details [here](https://www.kaggle.com/datasets/ahmedmohameddawoud/ford-gobike-system-data).

Special thanks to the Kaggle community and data contributors for making such valuable datasets available for analysis.
