
### Files and Folders

- **Report/**: This folder includes the assignment report, detailing the objectives, methodologies, results, and conclusions of the collaborative filtering project.
  
- **Code/**: Contains the Python code implementing collaborative filtering. The code performs data preprocessing, calculates similarity scores (cosine similarity and Pearson correlation), and provides recommendations based on both user-based and item-based collaborative filtering.

- **Data/**: This folder includes the preprocessed datasets used throughout the project. The final user-item matrix, located at `Data/formatted_csv/Final_user_matrix.csv`, contains the standardized data ready for collaborative filtering, with all transformations applied.

## Usage Instructions

1. **Data Preprocessing**: Ensure the `Final_user_matrix.csv` file is located in the correct path as specified. The code will automatically load this data for collaborative filtering tasks.

2. **Running the Code**: Navigate to the `Code/` directory and run the collaborative filtering script. The code will load the `Final_user_matrix.csv`, perform similarity calculations, predict ratings, and generate Top-N recommendations for users based on user-based and item-based approaches.

3. **Report Reference**: For a detailed explanation of the methods, results, and evaluations, refer to the report in the `Report/` folder.

## References

All references and documentation links related to the code, data sources, and methodologies are available in the report.

## Tools and Libraries

The project uses the following libraries:
- **Pandas** for data manipulation and handling missing values.
- **NumPy** for numerical operations.
- **scikit-learn** for cosine similarity calculations.
- **SciPy** for Pearson correlation.

For additional information, please refer to each library's official documentation in the report.

---

This README provides an overview of the repository contents, usage instructions, and references to further documentation. It ensures that users have a clear understanding of the project structure and steps needed to execute the code successfully.
