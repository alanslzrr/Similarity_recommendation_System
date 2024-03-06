# Tenant Compatibility Recommendation System

## Project Description
This project develops an interactive application with Streamlit to facilitate the search and recommendation of compatible tenants, based on a detailed analysis of personal habits, lifestyle preferences, and personality compatibility. It employs data processing techniques and machine learning algorithms to analyze an exhaustive dataset of tenants, providing precise insights and recommendations to improve the tenant selection process in residential properties.

### Technologies and Techniques Employed
The project integrates various data science and machine learning tools and techniques, including:

- **Streamlit**: For creating an interactive and user-friendly interface that allows users to easily interact with the recommendation model.
- **Pandas and Numpy**: Used for data manipulation and analysis, facilitating the management of the tenant dataset and data preparation for modeling.
- **Scikit-learn**: Employs preprocessing tools like `OneHotEncoder` to convert categorical variables into a format suitable for machine learning algorithms, and is used to develop classification or clustering models that could be at the heart of the recommendation system.
- **Matplotlib and Seaborn**: For data visualization, providing graphs and tables that allow for intuitive interpretation of tenant compatibility and other relevant metrics.

### Compatibility Analysis
The core of the recommendation system is based on advanced machine learning algorithms to assess compatibility between potential tenants. This analysis could include:

- **Clustering Techniques**: To group tenants with similar characteristics and preferences, facilitating the identification of compatible matches.
- **Principal Component Analysis (PCA)**: To reduce the dimensionality of the data and improve the efficiency of clustering or classification algorithms.
- **Recommendation Systems Based on Collaborative Filtering or Content**: Personalizing recommendations based on similarities between tenants and their preferences.


![ProcessFlowStreamlitApplicationt](./docs/ProcessFlowStreamlitApplication(7).png)
### Intuitive Interface with Streamlit
The application uses Streamlit to provide a smooth and dynamic user experience, where users can:

- Enter tenant preferences and requirements.
- View recommendations of compatible tenants.
- Explore detailed analyses and visualizations of compatibility.

## Project Structure

The **Tenant Compatibility Recommendation System** project is organized into several key files and directories that work together to provide a complete analysis and recommendation solution based on tenant data. Here is described the function and purpose of each important file within the project structure:

- **`app.py`**: This is the main Streamlit application script. It defines the user interface (UI) and handles user interaction with the application. Here, visualizations are set up, user inputs are captured, and the results of the tenant compatibility recommendations are displayed.

- **`ayudantes.py`**: Contains auxiliary and utility functions that are used throughout the project. This includes functions for data processing, generating specific visualizations, and any other recurring operation needed to support the main logic of the recommendation system.

- **`logica.py`**: Implements the core business logic of the project. Here are found the machine learning algorithms and methods used to analyze the tenant dataset, calculate compatibility metrics, and generate recommendations. This file is crucial for the operation of the recommendation system.

- **`dataset_inquilinos.csv`**: Is the main dataset used by the project. It contains detailed information about the tenants, including their personal preferences, habits, and other relevant attributes that are used to assess compatibility among them.

- **`metadatos.xlsx`**: Provides additional information and metadata about the tenant dataset. This file may include descriptions of the columns, details about data collection, and any other contextual information that helps to understand and work with the dataset.

### Code Organization

The code is structured in a modular way to promote reuse and facilitate maintenance. Each `.py` file focuses on specific aspects of the project, from the user interface to the data processing logic and backend operations. This modular organization allows the project to be scalable and easy to update or modify as needed.

### Visualizations and Data Analysis

Visualizations are generated using **Matplotlib** and **Seaborn**, integrated directly into the Streamlit interface through `app.py`. These visualizations are fundamental to presenting the results of the compatibility recommendations in an intuitive and accessible way for users.

### Data Processing and Analysis

Data preprocessing and analysis are carried out using **Pandas**, **Numpy**, and **Scikit-learn**, leveraging their extensive capabilities to handle complex datasets and apply machine learning techniques.

