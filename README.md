# Photovoltaic Energy: Self-Consumption and Cost Saving

This repository presents a comprehensive analysis of historical photovoltaic (PV) energy data, enabling consumers to gain valuable insights and perform cost-benefit analyses. By leveraging the provided Jupyter Notebook, consumers can harness the power of data to understand their PV energy generation, revenue components, and potential cost savings. As the demand for sustainable energy solutions continues to rise, more households are turning to photovoltaic systems for their electricity needs. However, many consumers face challenges in comprehending the complex energy data associated with their PV systems. This repository aims to bridge that gap by empowering consumers to gain valuable insights from the data that is available to them. 

## Data Analysis Process

The analysis followed the following steps:

1. **Data Loading**: The PV energy data was loaded from a CSV file, which contained information about energy generation at 15-minute intervals.

2. **Data Exploration**: The data was explored to understand its structure, including the time intervals, power generation values, and other relevant attributes.

3. **Time Segmentation**: The data was segmented based on time intervals, such as months, to observe seasonal variations in energy generation patterns. Representative day profiles for each month were visualized to understand the performance of the PV system throughout the year.

4. **Revenue Components**: Revenue components were calculated to quantify the financial benefits of PV energy generation. This included the calculation of the feed-in tariff (FIP) revenue, which is the revenue generated from injecting excess energy into the grid. The analysis also considered the concept of the loss factor, which incentivizes local energy production. By accounting for transformer loss and loss factors, the potential revenue enhancement and cost savings for homeowners relying on self-consumed energy were highlighted. Second Revenue generated from selling surplus energy to the market at the average market price was calculated. This revenue component accounted for the difference between PV energy production and load consumption, considering transformer loss and loss factor. The third revenue which is the cost savings resulting from self-consumption was quantified by multiplying self-consumed energy with the electricity price. This demonstrated the financial benefits of reducing dependence on grid electricity.

8. **Summary and Results**: The analysis results, including the revenue components and cost savings, were summarized to provide a comprehensive overview of the financial benefits associated with PV energy generation.

## Repository Contents

- `PV_Data_Analysis.ipynb`: The Jupyter Notebook containing the step-by-step analysis of the PV energy data.
- `data/`: This folder contains the dataset used for the analysis.

## How to Use

To reproduce or build upon this analysis, follow these steps:

1. Clone this repository to your local machine using `git clone https://github.com/[username]/photovoltaic-energy-analysis.git`.

2. Install the necessary dependencies by running `pip install -r requirements.txt`.

3. Open the Jupyter Notebook `PV_Data_Analysis.ipynb` and run each cell to execute the analysis step by step.

4. Feel free to modify the notebook to suit your specific requirements or extend the analysis further.

## Acknowledgements

The PV energy data used in this analysis was obtained from www.tudelft.nl. I would like to express our gratitude to the contributors to the dataset for making it publicly available.

## Contact Information

For any questions, feedback, or collaborations, please reach out to harpreets924@gmail.com


