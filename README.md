# LLM-Analysis

This repository contains analysis and visualizations of large language models (LLMs) using a dataset of various LLMs released since 2018. The analysis includes model counts by company, distribution of parameters and tokens, relationships between parameters and tokens, feature engineering, and detailed exploratory data analysis (EDA).

## Notebooks

### 1. Model Count by Company

- **Filename**: `Model_Count_by_Company_Analysis.ipynb`
- **Description**: This notebook analyzes the count of language models developed by each company. It includes visualizations with x-axis labels fixed to avoid overlapping.

### 2. Distribution of Parameters and Tokens

- **Filename**: `Distribution_of_Parameters_and_Tokens_Analysis.ipynb`
- **Description**: This notebook analyzes the distribution of parameters and tokens across different language models.

### 3. Relationship between Parameters and Tokens

- **Filename**: `Relationship_between_Parameters_and_Tokens_Analysis.ipynb`
- **Description**: This notebook analyzes the relationship between parameters and tokens across different language models.

### 4. Feature Engineering

- **Filename**: `Feature_Engineering_Analysis.ipynb`
- **Description**: This notebook includes feature engineering steps such as calculating missing ALScore values and exploring the impact of different architectures on model performance.

### 5. Predictive Modeling

- **Filename**: `Predictive_Modeling_Analysis.ipynb`
- **Description**: This notebook builds predictive models to estimate missing values (like tokens or ALScore) based on available data.

### 6. Detailed EDA

- **Filename**: `Detailed_EDA_Analysis.ipynb`
- **Description**: This notebook performs detailed exploratory data analysis (EDA), exploring trends over time (release date) and analyzing the impact of training datasets on model performance.

## Dataset

The dataset used in this analysis includes information on major LLMs released since 2018, such as the company, architecture, number of parameters, number of tokens, ALScore, training dataset, release date, and additional notes.


## License

This repository is licensed under the MIT License. See the LICENSE file for more information.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or suggestions.

## Acknowledgements

Special thanks to all contributors and the open-source community for their valuable tools and resources.


## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/debjit-mandal/LLM-dataset-Analysis.git
2. Navigate to the repository directory:
   ```bash
    cd LLM-dataset-Analysis
3. Open the notebooks using Jupyter Notebook or Jupyter Lab:
   ```bash
    jupyter notebook
----------------------------------------------------------------

Feel free to suggest any kind of improvements.