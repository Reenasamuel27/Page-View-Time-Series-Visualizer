# Page-View-Time-Series-Visualizer
# 📊 Page View Time Series Visualizer

This project is a time series data visualization tool built using `Pandas`, `Matplotlib`, and `Seaborn`. It uses data from the [freeCodeCamp Forum](https://freecodecamp.org/) to explore and visualize trends in daily page views.

## 📁 Project Structure

. ├── fcc-forum-pageviews.csv # Dataset ├── time_series_visualizer.py # Script with plotting functions ├── test_module.py # Unit tests └── README.md # Project documentation

markdown
Copy
Edit

## 🧪 Features

- **Line Plot**: Visualizes daily page views over time.
- **Bar Plot**: Shows average monthly page views grouped by year.
- **Box Plot**: Displays distributions and outliers across years and months.

---

## 🔧 Requirements

- Python 3.x
- Pandas
- Matplotlib
- Seaborn
- Pytest (optional for running tests)

Install dependencies with:

```bash
pip install -r requirements.txt
Or manually:

bash
Copy
Edit
pip install pandas matplotlib seaborn
🚀 Usage
To run the visualizations:

bash
Copy
Edit
python time_series_visualizer.py
The generated plots will be saved as image files:

line_plot.png

bar_plot.png

box_plot.png

🧪 Running Tests
To check your code against the test cases:

bash
Copy
Edit
pytest test_module.py
📝 Notes
The dataset is cleaned by removing the top and bottom 2.5% of page views to reduce noise.

Box plots help analyze both seasonal and yearly patterns.

Deprecation warnings due to np.float from Seaborn are safe to ignore and don’t affect functionality.

📷 Sample Output
Line Plot
Visualizes daily page views from 2016 to 2019.

Bar Plot
Shows monthly averages per year.

Box Plot
Year-wise and month-wise distribution of page views.

📚 License
This project is part of the freeCodeCamp Data Analysis with Python curriculum and is licensed for educational use.

🙌 Acknowledgements
Data from the freeCodeCamp forum.

Project boilerplate by freeCodeCamp.
