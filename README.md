# Slice Insights-Tech\_Crunch\_Task3

**Exploratory data analysis of pizza place sales: revenue trends, peak hours, and best-sellers.**

## Table of Contents

* [Project Overview](#project-overview)
* [Data](#data)
* [Installation](#installation)
* [Usage](#usage)
* [Analysis Highlights](#analysis-highlights)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)

## Project Overview

Slice Insights-Tech\_Crunch\_Task3 performs an in-depth exploration of a fictitious pizza restaurant’s sales data over one year. This analysis was completed as Task 3 for the Tech Crunch assignment. The analysis covers:

* Total revenue and quantity sold
* Peak hours and busiest days
* Top and under-performing pizzas
* Monthly sales trends
* Ingredient popularity and order-level metrics

## Data

The dataset is provided as four CSV files within `Pizza+Place+Sales.zip`:

1. **orders.csv**: order\_id, date, time
2. **order\_details.csv**: order\_details\_id, order\_id, pizza\_id, quantity
3. **pizzas.csv**: pizza\_id, pizza\_type\_id, size, price
4. **pizza\_types.csv**: pizza\_type\_id, name, category, ingredients

These are merged into a single DataFrame for analysis.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/<your-username>/Slice-Insights-Tech_Crunch_Task3.git
   cd Slice-Insights-Tech_Crunch_Task3
   ```
2. Create a virtual environment and install dependencies:

   ```bash
   python3 -m venv venv
   source venv/bin/activate  # macOS/Linux
   venv\\Scripts\\activate   # Windows
   pip install -r requirements.txt
   ```

## Usage

1. Place `Pizza+Place+Sales.zip` in the project root.
2. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```
3. Open and run `slice_insights_analysis.ipynb` to reproduce the analysis and visualizations.

## Analysis Highlights

* **Total Revenue**: \$817,860.05
* **Total Quantity Sold**: 49,574 pizzas
* **Peak Hour**: 12:00 (noon)
* **Busiest Day**: Friday
* **Top 5 Pizzas**: Classic Deluxe, Barbecue Chicken, Hawaiian, Pepperoni, Thai Chicken
* **Under-performers**: Brie Carre, Mediterranean, Calabrese, Spinach Supreme, Soppressata
* **Average Order Value**: \$38.31

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for improvements or new analyses.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

## Contact

Completed by **Oluwagbotemi Victor**, the analyst who performed Task 3 for Tech Crush. For questions or feedback, please contact \[(oluwafemhi08@gmail.com)].
