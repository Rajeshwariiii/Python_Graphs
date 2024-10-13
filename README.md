
# Pir Charts Visualization
# Overview 
The purpose of these pie charts is to visually present the distribution of survey responses from two different groups: Non-Student Adults and College Students. The pie charts offer a more intuitive understanding of how the responses are distributed within each group. Each slice represents a different survey response, and the size of the slice reflects the proportion of that response within the total.

By showing these distributions side by side,it becomes simple to compare the response patterns of Non-Student Adults and College Students, identifying similarities or differences in how these two groups responded to the same survey questions.

# Comparison of Different Responses
Non-Student Adults vs. College Students: By observing the size of the slices and their respective percentages, we can quickly identify how each group feels or thinks about the survey topic.
For example, if one slice is significantly larger in one pie but smaller in the other, it indicates that one group has a stronger inclination towards that response.
Frequency and Proportion: Each slice represents the frequency of a particular response

# Enhancements 

- **Custom Colors:**
Each group has its own distinct set of colors (colors1 for Non-Student Adults and colors2 for College Students). For instance, if the same response appears in both groups, we can instantly compare it based on the color used.

- **Exploded Slices:**
The explode=[0.05]*3 effect slightly separates each slice from the center, making the differences between responses more visible. 
It improves readability, making it easier to differentiate one response from another, particularly in more crowded pie charts.

- **Shadow Effect:**
The shadow=True feature creates a subtle shadow under the pie chart, adding depth. 

- **Side-by-Side Layout:**
By positioning the two charts side by side using the subplot(1, 2, x) structure, we can compare the data directly and easily. This layout helps to contrast the two groups at a glance, showing how one group's responses might differ from the other's.
The **plt.tight_layout()** ensures that both pie charts fit neatly on the same screen without overlapping, giving a clean, professional look to the presentation.

# Death Counts by Month Visualization
# Overview
This project visualizes the number of doctor-certified deaths for the years 2022, 2023, and 2024. The data is presented using a grouped bar chart that compares the death counts across several months (January to May) for each of these years. The visualization is built using Python's Pandas and Matplotlib libraries.

# Features
- Data Upload: The Excel file containing death count data is uploaded and read into a Pandas DataFrame for easy manipulation and analysis.
- Data Plotting: The grouped bar chart allows for a side-by-side comparison of monthly death counts over the years 2022, 2023, and 2024.
- Customizations:
Custom x-axis labels for months.
Grouped bar layout for visual comparison between years.
Color-coded bars for each year.
Legends and titles for easy interpretation.

