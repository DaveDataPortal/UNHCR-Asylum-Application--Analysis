```markdown
# Analysis of UNHCR Asylum Application Data (2010-2023)

This project analyzes the asylum application data provided by the United Nations High Commissioner for Refugees (UNHCR) from 2010 to 2023. The analysis aims to provide insights into various aspects of asylum applications, including the countries of origin, destination countries, application types, and processing entities.

## Dataset

The dataset used in this analysis is the `asylum-applications.csv` file, which contains information about asylum applications received by different countries from various countries of origin, along with the application type and processing entity.

## Analysis

The analysis is performed using Python and various data visualization libraries such as Matplotlib and Seaborn. The following analyses are included:

1. **Number of Applications from Different Countries**: This section visualizes the total number of asylum applications received from different countries of origin, sorted in descending order.

2. **Top 10 Destination Countries for Asylum Seekers**: This section displays a bar chart showing the top 10 destination countries with the highest number of asylum applications received.

3. **Least 10 Destination Countries for Asylum Seekers**: This section presents a horizontal bar chart showing the 10 destination countries with the least number of asylum applications received.

4. **Relationship between Number of Applications and Country of Origin**: This section explores the relationship between the number of asylum applications and the country of origin using a scatter plot.

5. **Total Applications to Germany**: This section focuses on the destination country that received the highest number of asylum applications and visualizes the total applications from different countries of origin to that destination country.

6. **Total Asylum Applications by Application Type (Descending Order)**: This section displays the total number of asylum applications received for different application types, sorted in descending order.

7. **Total Asylum Applications by Application Type and Country**: This section visualizes the total number of asylum applications received by different destination countries, categorized by application type.

8. **Country of Origin with the Highest Number of Applications per Year**: This section identifies the country of origin with the highest number of asylum applications for each year and visualizes the trend over time.

9. **Distribution of Processing Entities Across Countries**: This section analyzes the distribution of processing entities (authorities) across different destination countries using a horizontal bar chart.

## Requirements

To run this analysis, you will need the following dependencies:

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

You can install the required dependencies using pip:

```
pip install pandas numpy matplotlib seaborn
```

## Usage

1. Clone or download this repository.
2. Ensure that the `asylum-applications.csv` dataset is present in the `Datasets` folder.
3. Run the `Analysis of UNHCR-Asylum-Application from 2010-2023 (1).py` script to generate the visualizations and analysis.

Feel free to explore and modify the code to perform additional analyses or customize the visualizations according to your requirements.

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
```
