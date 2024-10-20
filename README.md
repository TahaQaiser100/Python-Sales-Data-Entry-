# Sales Tracking System

A Python-based sales tracking application that allows users to add sales records, view and filter sales history, and visualize sales data with charts. It uses Pandas for data management, Matplotlib for visualizations, and can export sales data to CSV for future reference.

## Features

- **Add New Sales**: Record product name, quantity sold, sales value, and region.
- **View Sales History**: Display a full sales history in a tabular format.
- **Filter Sales by Date**: Filter sales records by a specified date range.
- **Visualize Sales Trends**: Plot sales data using Matplotlib for graphical analysis.
- **Save Data to CSV**: Export sales records to a CSV file for storage or sharing.
- **Sales Insights**: Calculate total sales, average sales, and total quantity sold.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/sales-tracking-system.git
   ```
2. Navigate to the project directory:
   ```bash
   cd sales-tracking-system
   ```
3. Install the required Python libraries:
   ```bash
   pip install pandas matplotlib
   ```

## Usage

1. Run the script:
   ```bash
   python sales_tracking.py
   ```
2. Follow the menu options:
   - Add a new sale
   - View sales history
   - Filter sales by date and view a sales chart
   - Save sales data to a CSV file
   - View total sales, average sales, and total quantity sold

## Example

### Adding a Sale
```bash
Please enter the date (dd-mm-yyyy):
> 12-10-2024
Please enter the product name:
> smartphone
Please enter the quantity sold:
> 5
Please enter the Sales Value:
> 3500
Please enter the sale region (Country):
> UK
Sale successfully added!
```

### Sales Visualization
![Sales Chart Example](path-to-sales-chart-screenshot.png)

## Requirements

- Python 3.x
- Pandas (`pip install pandas`)
- Matplotlib (`pip install matplotlib`)

## Contributing

Contributions are welcome! Feel free to fork the repository and submit pull requests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
