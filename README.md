# Finance Dash

A personal finance dashboard built with Streamlit that helps you categorize and visualize your transaction data.

## Live Demo

Try it out: [Finance Dash Live Demo](https://finance-dash.streamlit.app/)

## Features

- **Transaction Import**: Upload CSV files from your bank statements
- **Automatic Categorization**: Categorize transactions based on keywords
- **Custom Categories**: Create and manage your own spending categories
- **Interactive Visualization**: View your spending patterns with charts and graphs
- **Data Editing**: Manually edit transaction categories as needed
- **Persistent Settings**: Your categories and rules are saved between sessions

## Prerequisites

- Python 3.8+
- Required Python packages:
  ```
  pip install streamlit pandas plotly
  ```

## Setup

1. Clone the repository:

   ```
   git clone https://github.com/yourusername/finance-dash.git
   cd finance-dash
   ```

2. Install dependencies:

   ```
   pip install -r requirements.txt
   ```

3. Run the application:
   ```
   streamlit run main.py
   ```

## Usage

1. **Upload Transactions**: Use the file uploader to import your bank statement CSV
2. **Manage Categories**: Create custom categories and add keywords for automatic categorization
3. **Edit Transactions**: Manually adjust categories for individual transactions
4. **Analyze Spending**: View charts showing your spending breakdown by category

## CSV Format

Your bank statement CSV should include the following columns:

- Date
- Details (transaction description)
- Amount
- Debit/Credit (optional)

## How It Works

- Transactions are loaded from CSV files
- The system attempts to categorize transactions based on keywords
- You can manually edit categories for better accuracy
- Visualizations help you understand your spending patterns
- All settings are saved to your browser's local storage

## Files

- `main.py`: The main application with the Streamlit interface
- `requirements.txt`: List of required Python packages
- `categories.json`: Saved category definitions (created on first run)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
