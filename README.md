# Analyse user engagement across internship domains
## Overview

This project analyzes user engagement with internships across various domains. It aims to identify the most popular and emerging internship fields using visual insights and data-driven analysis.

## Key Features

1. **Data Analysis**: Explore trends in internship applications and participation rates.
2. **Visualizations**: Gain insights through bar charts, pie charts, and time-series plots.
3. **Technologies Used**:

   * Python
   * Pandas, Matplotlib, Seaborn for data analysis and visualization

## Folder Structure

```
📁 InternshipEngagementAnalysis
|-- user_engagement_dataset.csv
|-- analysis.ipynb
|-- README.md
```

* **data**: Contains the dataset (`user_engagement_dataset.csv`).
* **code**: Contains the script for data analysis and visualization (`analysis.py`).

## How to Run the Project

1. Clone the repository:

   ```bash
   git clone <repository_url>
   cd InternshipEngagementAnalysis
   ```

2. Install required Python libraries:

   ```bash
   pip install pandas matplotlib seaborn
   ```

3. Execute the script:

   ```bash
   python code/analysis.py
   ```

4. View the generated insights and visualizations in your terminal or local environment.

## Dataset

The dataset contains the following columns:

| Column Name            | Description                                |
| ---------------------- | ------------------------------------------ |
| `Internship_ID`        | Unique ID of the internship                |
| `Domain`               | Internship domain (e.g., AI/ML, Web Dev)   |
| `Student_ID`           | Unique ID of the student                   |
| `University`           | University of the applicant                |
| `Year_of_Study`        | Current year of study of the student       |
| `Program`              | Program enrolled (e.g., MBA, M.Tech)       |
| `Application_Date`     | Date of application submission             |
| `Status`               | Application status (Accepted/Rejected)     |
| `Participation`        | Whether the student participated (Yes/No)  |
| `Clicks_on_Internship` | Number of clicks on the internship details |

## Visualizations

1. **Most Popular Domains**: Bar chart showing applications per domain.
2. **Participation Rate**: Pie chart visualizing participation percentages.
3. **Applications Over Time**: Line plot showing application trends.
4. **University Analysis**: Bar chart of applications by university.
5. **Clicks Analysis**: Bar chart of average clicks per domain.

## Contribution

Feel free to contribute by:

* Adding more analysis features.
* Improving the visualizations.
* Enhancing the dataset with real-world data.

## License

This project is licensed under the MIT License. See the LICENSE file for details.


Thank you for exploring the project!
