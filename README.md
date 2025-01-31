
# Electric Vehicle (EV) Data Analysis

### Overview


This project focuses on analyzing the trends and statistics of electric vehicles (EVs) using a dataset obtained from Statso.io. The dataset includes information on various attributes of electric vehicles, such as **VIN, county, city, state, model year, make, model, electric vehicle type, clean alternative fuel vehicle eligibility, electric range,** and more. The analysis aims to provide insights into the adoption of electric vehicles over time and other relevant trends.

  

### Dataset

  

The dataset used in this analysis is named Electric_Vehicle_Population_Data.csv. It contains detailed information about electric vehicles registered till March 2024. The dataset includes the following key columns:

  

**VIN (1-10)**: Vehicle Identification Number (first 10 characters)

**County**: The county where the vehicle is registered

**City**: The city where the vehicle is registered

**State**: The state where the vehicle is registered

**Postal Code**: The postal code of the vehicle's location

**Model Year**: The year the vehicle was manufactured

**Make**: The manufacturer of the vehicle

**Model**: The model of the vehicle

**Electric Vehicle Type**: The type of electric vehicle (e.g., Battery Electric Vehicle (BEV))

**Clean Alternative Fuel Vehicle (CAFV) Eligibility**: Eligibility status based on battery range

**Electric Range**: The range of the vehicle on a full charge

**Base MSRP**: The manufacturer's suggested retail price

**Legislative District**: The legislative district of the vehicle's location

**DOL Vehicle ID**: The Department of Licensing vehicle ID

**Vehicle Location**: The geographical location of the vehicle

**Electric Utility**: The electric utility provider

**2020 Census Tract**: The census tract based on the 2020 Census

### Analysis


The analysis is performed using Python and several data analysis libraries, including Pandas, Matplotlib, and Seaborn. The key steps in the analysis include:

  

**Data Loading**: The dataset is loaded into a Pandas DataFrame for further analysis.

**Data Exploration**: The first few rows of the dataset are displayed to get an initial understanding of the data.

**EV Adoption Over Time**: A bar plot is created to visualize the adoption of electric vehicles over the years. The plot shows the number of vehicles registered each year, providing insights into the growth of EV adoption.

### Visualizations

  

The project includes visualizations to better understand the trends in EV adoption:

  

**EV Adoption Over Time**: A bar plot showing the number of electric vehicles registered each year from 2016 to 2023. The plot highlights the increasing trend in EV adoption over the years.

### Requirements

  

To run the analysis, you need the following Python libraries:

  

**Pandas**: For data manipulation and analysis.

**Matplotlib**: For creating static, animated, and interactive visualizations.

**Seaborn**: For statistical data visualization.

You can install these libraries using pip:
```bash
pip install pandas matplotlib seaborn
```

### Usage



Clone the repository to your local machine.

Ensure you have the required Python libraries installed.

Run the Jupyter Notebook ev_analysis.ipynb to perform the analysis and generate visualizations.

### Conclusion

  

This project provides a comprehensive analysis of electric vehicle adoption trends using real-world data. The visualizations help in understanding how EV adoption has evolved over the years and can be used to make informed decisions or further research in the field of electric vehicles.

### Acknowledgments

  

Statso.io for providing the dataset.

Pandas, Matplotlib, and Seaborn for providing the tools necessary for data analysis and visualization.