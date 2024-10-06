# Survival Insights: Exploratory Data Analysis (EDA) on Spaceship Survival Dataset

## Project Description:
This project involves performing Exploratory Data Analysis (EDA) on a spaceship survival dataset to uncover key insights about passengers likely to be transported. The dataset includes various attributes such as home planet, CryoSleep status, cabin type, destination, age, spending on different services (e.g., RoomService, Spa, FoodCourt), and more.

## Key Features:
1. **Data Cleaning**: 
   - Handled missing values in numerical and categorical columns.
   - Imputed missing ages with the median, CryoSleep status with `False`, and spending columns with `0` where applicable.
   
2. **Data Exploration**: 
   - Analyzed the dataset’s structure, identified missing values, and examined summary statistics.

3. **Data Visualization**:
   - **Age Distribution**: Displayed the distribution of passengers’ ages.
   - **CryoSleep vs Transported**: Analyzed whether passengers in CryoSleep were more likely to be transported.
   - **HomePlanet Distribution**: Visualized the likelihood of transportation based on the home planet.
   - **Spending vs Transported**: Investigated the relationship between passengers' spending patterns and their chances of being transported.

## Key Insights:
1. **Age**: Most passengers are between 20 and 30 years old.
2. **CryoSleep**: Passengers in CryoSleep are more likely to be transported.
3. **HomePlanet**: Europa has the highest number of transported individuals, while Earth has the highest number of non-transported individuals.
4. **Spending**: Higher spenders are more likely to be transported.

## Technologies Used:
- **Python**: Programming language used for analysis.
- **Pandas & NumPy**: Libraries for data manipulation and exploration.
- **Seaborn & Matplotlib**: Libraries for data visualization.

## Files Included:
- **`spaceship_survival_EDA.ipynb`**: Contains the complete Python notebook for data cleaning, exploration, and visualization.

## Conclusion:
This EDA provides valuable insights into the factors that influence a passenger's likelihood of being transported on the spaceship, with key takeaways related to age, CryoSleep, home planet, and spending behavior.

