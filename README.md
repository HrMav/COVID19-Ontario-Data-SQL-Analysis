# COVID19-Ontario-Data-SQL-Analysis

This repository contains SQL queries and data analysis for COVID-19 vaccine and testing information in Ontario. The data encompasses various hospitals and locations within the province and aims to provide insightful dashboards through Apache Superset.

## Description

The project uses two main datasets: `ONCOVID19vaccine` and `ONCOVID19testing`, which have been uploaded to a MySQL database. These datasets include detailed records about COVID-19 vaccination and testing within Ontario's healthcare facilities.

## Installation and Setup

To get started with this project:

1. Clone the repository to your local machine.
2. Install MySQL and set up a local server.
3. Import the provided CSV files into your MySQL database using the provided schema.
4. Ensure you have Apache Superset installed and configured to connect to your MySQL database.

## Usage

Inside the `sql-queries` directory, you will find several SQL query files. These files contain SQL statements designed to extract meaningful information from the datasets, which can then be visualized in Apache Superset.

To use these queries:

1. Open your MySQL workbench or command-line tool.
2. Select the appropriate database.
3. Execute the SQL queries.
4. Use the results of these queries as the basis for your dashboards in Apache Superset.

## Contributing

Contributions to this project are welcome. To contribute:

1. Fork the repository.
2. Create a new branch for your feature (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a pull request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Thanks to the Ontario Health Data Platform for providing the data used in this project.
- Special thanks to all healthcare workers and data scientists who are working tirelessly to combat COVID-19.
