# Complaint Status Dashboard

A web-based dashboard for monitoring and analyzing complaint inspection data. This dashboard provides visual insights into complaint statistics with various filtering options and interactive charts.

## Features

- **Interactive Data Visualization**: Multiple charts showing different aspects of complaint data
- **Drilldown Capability**: Interactive drilldown functionality in charts for detailed data analysis
- **Flexible Filtering Options**:
  - Year/Month selection with multi-select capability
  - Date range picker
  - Quick filters for "Yesterday" and "Last 7 Days"
- **Real-time Data Updates**: Fetches data from a backend API
- **Responsive Design**: Works on both desktop and mobile devices
- **Export Capabilities**: Charts can be exported in various formats

## Charts Included

1. Claim Processed Chart (with drilldown functionality)
2. Name1 Chart (with drilldown functionality)
3. Zones Chart (with drilldown functionality)
4. Brand Name Chart (with drilldown functionality)
5. Used Period Chart (with drilldown functionality)
6. Equal Quality Chart (with drilldown functionality)
7. City Chart (with drilldown functionality)

Each chart supports drilldown functionality, allowing users to:
- Click on chart elements to view more detailed information
- Navigate through hierarchical data levels
- Return to parent levels for broader analysis
- Export drilldown data for further analysis

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Bootstrap 5.3.0
- jQuery 3.6.0
- Highcharts
- Moment.js
- Daterangepicker

## Setup and Installation

1. Clone the repository
2. Ensure all required files are in the same directory:
   - `index.html`
   - `style.css`
   - `style2.css`
   - `script.js`
   - `script2.js`
   - `script3.js`
   - `icons8-favicon-94.png`

3. The dashboard requires a backend API endpoint at `http://192.168.1.209:5055/callcenterreportdata`. Make sure this endpoint is accessible and returns the required data format.

4. Open `index.html` in a web browser to view the dashboard.

## Usage

1. Use the dropdown menu to select specific year/month combinations
2. Use the date range picker to select custom date ranges
3. Use the "Yesterday" and "-7Day's" buttons for quick filtering
4. Interact with charts to view detailed information
5. Use the "Data-Table" button to navigate to the data table view

## Project Structure

- `index.html`: Main dashboard interface
- `style.css` & `style2.css`: Custom styling
- `script.js`: Main JavaScript functionality
- `script2.js`: Additional JavaScript functionality
- `script3.js`: Data table functionality
- `icons8-favicon-94.png`: Dashboard favicon

## Dependencies

The project uses the following CDN-hosted dependencies:
- Bootstrap 5.3.0
- jQuery 3.6.0
- Moment.js
- Daterangepicker
- Highcharts and its modules

## Browser Compatibility

The dashboard is compatible with modern web browsers including:
- Google Chrome
- Mozilla Firefox
- Microsoft Edge
- Safari

## License

This project is proprietary software. All rights reserved. 