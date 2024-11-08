# Data_visualization_project
**Data Visualization Web Application**
This is a simple web-based data visualization tool built using Streamlit. 
The application allows users to upload a CSV file and interactively explore and visualize data. 
It supports visualizations like histograms for numerical data and bar charts for categorical (nominal) data.

**Features**

. File Upload: Upload your CSV dataset to analyze.
. Interactive Column Selection: Choose a column from your dataset to visualize.
. Numeric Data Visualization: Automatically generates a histogram for numeric columns.
. Categorical Data Visualization: Automatically generates a bar chart for non-numeric (nominal) columns.
. Easy-to-Use Interface: Simple and intuitive interface built with Streamlit.

**Requirements**

To run this project locally, you need to install the following dependencies:

Streamlit: Framework to build the web application.
Pandas: Library for data manipulation and reading CSV files.
Matplotlib: Library for creating static, animated, and interactive visualizations in Python.
Seaborn: Statistical data visualization library built on top of Matplotlib.

**You can install these dependencies using pip. Run the following command:
!pip install streamlit pandas matplotlib seaborn**

**How to Run**
1. Clone the Repository: If you haven't already, clone the repository to your local machine.
   git clone https://github.com/yourusername/data-visualization-streamlit.git
cd data-visualization-streamlit


2. Install the Dependencies: Ensure that the required libraries are installed by running the following command:
   pip install -r requirements.txt

3. Run the Streamlit App: Use the following command to start the Streamlit app:
   streamlit run app.py

Replace app.py with the name of the file that contains your code (e.g., data_viz_app.py).

4. Access the App: Once the app starts, open your web browser and go to the URL provided in the terminal (usually http://localhost:8501).


**Features in Detail**

**1. Upload a Dataset**
  . Users can upload a CSV file via the file uploader widget.
  . Once uploaded, the dataset is displayed in a preview format.

**2. Column Selection**
  . A dropdown allows users to select any column from the dataset.
  . Based on the column's data type (numeric or categorical), the app will display the appropriate visualization.

**3. Numeric Data Visualization**
  . If the selected column contains numeric data, the app generates a histogram.
  . The histogram displays the distribution of values in that column.

  **4. Categorical Data Visualization**
    . If the selected column contains categorical (nominal) data, the app generates a bar chart.
    . The bar chart displays the count of each unique category in the column.

**Example**
Upload your CSV: Click on the "Upload a dataset" button and select a CSV file.
Choose a Column: After the data is loaded, select a column from the dropdown.
View Visualization: The app will display a histogram for numeric data or a bar chart for categorical data.

