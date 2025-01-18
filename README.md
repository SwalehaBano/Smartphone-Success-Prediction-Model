# Smartphone Success Prediction Model 

This project is a web application for analyzing a smartphone dataset. The app allows users to explore key insights, visualize data, and interact with smartphone specifications such as brand, price, RAM, storage, camera specifications, and more.

## Features

- **Dataset Overview**: View the total number of rows, brands, and dataset columns.
- **Brand-wise Price Analysis**: Explore the price ranges for different smartphone brands.
- **Visualization**: Analyze data through interactive graphs (e.g., price vs battery capacity).
- **Upload New Dataset**: Upload your own dataset for analysis (optional feature).
- **Simple and Intuitive Design**: A clean and user-friendly interface for easy navigation.

## Tech Stack

- **Backend**: Flask (Python)
- **Frontend**: HTML, CSS
- **Data Processing**: Pandas, Matplotlib
- **Deployment**: Flask development server (can be deployed on Heroku, PythonAnywhere, etc.

## Getting Started

### Prerequisites

- Python 3.x installed on your system
- Flask and other dependencies (install using `pip`)
  
The dataset should have the following columns:

Column Name	Description
Brand	Brand name of the smartphone
Model	Model name of the smartphone
Color	Available color of the smartphone
Price	Price of the smartphone
Review	Average customer review score
RAM	RAM capacity (in GB)
ROM	Storage capacity (in GB)
Height	Height of the smartphone (in mm)
Width	Width of the smartphone (in mm)
Main_Cam	Megapixels of the main camera
Extra_Cam	Megapixels of the extra camera (if any)
Front_Cam	Megapixels of the front-facing camera
Battery	Battery capacity (in mAh)
Ensure the dataset is in CSV format.

Features to Add in Future
Interactive filtering and sorting of smartphones based on features.
Advanced data visualizations (e.g., bar charts, pie charts).
Predictive analysis for smartphone success using machine learning models.
Contributing
Contributions are welcome! Feel free to fork the repository, make your changes, and submit a pull request.

Acknowledgments
Data analysis and visualization powered by Pandas and Matplotlib.
Web application framework provided by Flask.
