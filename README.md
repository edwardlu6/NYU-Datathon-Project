# Datathon Project

This repository contains the code and data preprocessing steps for a datathon project focusing on identifying at-risk data points using various data features and applying the K-Nearest Neighbors (KNN) algorithm.

## Notebooks

### Datathon_KNN.ipynb
<a href="https://colab.research.google.com/github/KavyaS1/Possions-Croissants-/blob/main/Datathon_KNN.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

This notebook implements the K-Nearest Neighbors (KNN) algorithm to identify at-risk data points from the dataset. Out of 6279 data points, 595 have been flagged as at risk. The notebook provides a detailed analysis and steps for implementing the KNN algorithm.

### Datathon_Preprocessing.ipynb
<a href="https://colab.research.google.com/github/KavyaS1/Possions-Croissants-/blob/main/Datathon_Preprocessing.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

This notebook covers the preprocessing steps necessary for preparing the data for analysis. It includes:
- Risk Scores
- Housing Data
- Poverty Information
- Income Data
- Financial Data
- Dropping Null Rows
- Correlation Matrix
- Adding "At Risk" Column
- Stacking all State-county statistics dataframes into one

## Project Structure

- `Datathon_KNN.ipynb`: Implementation of the KNN algorithm.
- `Datathon_Preprocessing.ipynb`: Data preprocessing steps.

## Getting Started

To explore and run the notebooks, you can open them in Google Colab by clicking the badges above. Make sure to have your dataset prepared and uploaded in the correct path specified within the notebooks.

### Prerequisites

- Python 3.x
- Jupyter Notebook or Google Colab
- Necessary Python libraries (specified within each notebook)

### Running the Notebooks

1. Clone this repository to your local machine:
    ```bash
    git clone https://github.com/your-username/your-repository.git
    ```
2. Navigate to the cloned repository:
    ```bash
    cd your-repository
    ```
3. Open the notebooks in Jupyter or Colab and run the cells step-by-step.

## Contributing

Contributions are welcome! If you have any improvements or suggestions, feel free to create a pull request or open an issue.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

Thanks to the datathon organizers and the community for their support and resources.

## Team Members

- Reva Sharma
- Kavya Shyam
- William Zhang
- Edward Lu
