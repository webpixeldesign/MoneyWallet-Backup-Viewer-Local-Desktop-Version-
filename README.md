# MoneyWallet-Backup-Viewer-Local-Desktop-Version-

MoneyWallet Backup Viewer (Local Desktop Version)
A simple, client-side HTML, CSS, and JavaScript web application to open and view transaction data from MoneyWallet Android app backup files (database.json). This tool allows users to easily access and review their past financial records locally in their browser without needing the original app or an internet connection.

Features
Local File Processing: Opens and parses database.json (MoneyWallet backup) files directly in your browser. No data is uploaded to any server.

Transaction Display:

Clear, tabular view of all transactions.

Displays key details: Date/Time, Description, Category, Amount (with currency symbol), Wallet, Notes, and linked People.

Correctly formats amounts based on currency decimals and indicates income/expenses.

Monthly Grouping:

Transactions are grouped by month and year.

Each month starts with a summary row showing:

Month and Year

Total Income for the month

Total Expenses for the month

Net financial change for the month

Sorting:

Default sort: Transactions are displayed chronologically (most recent first within each month).

Clickable "Amount" header to sort transactions by amount (Ascending/Descending/Default).

Filtering:

Global Search: Search across descriptions, notes, categories, wallets, and people.

Date Range: Filter transactions between a specific start and end date.

Category Filter: Select one or more categories to view.

Wallet Filter: Select one or more wallets to view.

Filters can be combined and reset easily.

User-Friendly Interface:

Clean and intuitive layout for desktop viewing.

Sticky table headers and month overview rows for easier navigation of large datasets.

Clear visual distinction for income and expenses.

How to Use
Download:

Download the moneywallet_viewer.html file (or the equivalent HTML file you have for this version).

Prepare Your Data:

Ensure you have your MoneyWallet backup file. This is typically named database.json.

Option 1: Auto-Load (Recommended for Frequent Use)

Place the moneywallet_viewer.html file and your database.json file in the exact same folder on your computer.

Open moneywallet_viewer.html in your web browser. The application will attempt to automatically load database.json.

Note: Some browsers might have security restrictions that prevent direct local file access. If auto-load fails, use Option 2.

Option 2: Manual File Selection

Open moneywallet_viewer.html in your web browser.

Click the "Choose File" button (usually in the top-right corner).

Select your database.json backup file from your computer.

View Your Data:

Your transactions will be displayed, grouped by month.

Use the filter and sort controls at the top to navigate and analyze your data.

Technical Details
Frontend: Pure HTML, CSS, and JavaScript.

No Backend: All operations are performed client-side.

Data Privacy: Your financial data remains on your computer and is not transmitted anywhere.

To-Do / Potential Future Enhancements (for this version)
More advanced charting or visualization.

Export filtered data to CSV.

Customizable themes.

Contributing
Since this is a personal utility, direct contributions might not be the focus. However, feel free to fork the repository, adapt it for your own needs, or suggest improvements.

Disclaimer
This tool is provided as-is. Always ensure you have backups of your original MoneyWallet data. The developer is not responsible for any data loss or misinterpretation.
