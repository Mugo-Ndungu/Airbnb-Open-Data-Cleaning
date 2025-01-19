# Airbnb-OpenData-Cleaning

This repository focuses on cleaning and transforming Airbnb open data using Python Pandas and Jupyter Notebooks. The goal is to enhance the dataset's quality, readability, and consistency, making it suitable for further analysis and insights.

## Project Overview

In this project, I perform a series of data cleaning and transformation steps to prepare the Airbnb open dataset for analysis. The steps include:

1. **Eliminating Redundant Columns**: Streamline the dataset by removing unnecessary columns to enhance clarity and efficiency.
2. **Renaming Columns**: Standardize column names for better readability and consistency.
3. **Removing Duplicates**: Ensure data integrity by identifying and eliminating duplicate records.
4. **Cleaning Individual Columns**: Conduct thorough cleaning of each column to correct inconsistencies and improve data quality.
5. **Handling Missing Values**: Address and remove NaN values to ensure completeness and reliability of the dataset.
6. **Exploring Additional Transformations**: Evaluate the need for further data transformations to optimize the dataset for analysis.

## Files

- **`Airbnb_Open_Data.csv`**: The raw Airbnb open dataset.
- **`Cleaned_Airbnb_open_data.csv`**: The cleaned Airbnb open dataset.
- **`Notebook.ipynb`**: Jupyter Notebook containing the data cleaning and transformation process.
- **`README.md`**: Project overview and documentation.

## Data Cleaning Steps

### 1. Eliminating Redundant Columns

Streamlined the dataset by removing unnecessary columns to enhance clarity and efficiency.

### 2. Renaming Columns

Standardized column names for better readability and consistency.

### 3. Removing Duplicates

Ensured data integrity by identifying and eliminating duplicate records.

### 4. Cleaning Individual Columns

Conducted thorough cleaning of each column to correct inconsistencies and improve data quality. Specific actions included:
- Resetting the DataFrame index.
- Converting the `instant_bookable` column to binary values.
- Standardizing the `host_identity_verified` column to uppercase.

### 5. Handling Missing Values

Addressed and removed NaN values to ensure completeness and reliability of the dataset.

### 6. Exploring Additional Transformations

Evaluated the need for further data transformations to optimize the dataset for analysis. Specific actions included:
- Cleaning the `price` column by removing dollar signs, commas, and spaces, and converting it to an integer type.
- Saving the cleaned dataset to a new CSV file named `Cleaned_Airbnb_open_data.csv`.

## How to Use

1. **Clone the Repository**:
   ```sh
   git clone https://github.com/yourusername/Airbnb-OpenData-Cleaning.git
   ```

2. **Navigate to the Project Directory**:
   ```sh
   cd Airbnb-OpenData-Cleaning
   ```

3. **Open the Jupyter Notebook**:
   ```sh
   jupyter notebook Notebook.ipynb
   ```

4. **Run the Cells**: Execute the cells in the Jupyter Notebook to perform the data cleaning and transformation steps.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request if you have any suggestions or improvements.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
