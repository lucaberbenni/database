# MySQL Sales Reporting Project

This project is a demonstration of database operations using MySQL and Python. It's designed to showcase various SQL techniques, such as table creation, data insertion, and writing stored procedures, in the context of a restaurant management system.

## Features

- **Database Initialization**: Setup scripts to create and initialize a database called `little_lemon_db`.
- **Menu Management**: Scripts to create, populate, and query a `MenuItems` table containing different dishes offered by the restaurant.
- **Employee Management**: Tools to manage restaurant employees, including roles like managers, waiters, and receptionists.
- **Booking System**: A rudimentary booking system to handle customer reservations.
- **Sales Reporting**: A stored procedure to generate basic sales reports, showcasing metrics like total, average, minimum, and maximum bill amounts.
- **Connection Pooling**: Demonstrates the use of connection pooling for efficient database connections.

## Installation and Setup

1. **Clone the Repository**:
    ```
    git clone https://github.com/lucaberbenni/database.git
    ```

2. **Install Dependencies**:
    Navigate to the project directory and run:
    ```
    pip install -r requirements.txt
    ```

3. **Setup MySQL**:
    Ensure you have MySQL installed and running. Update the database connection parameters as needed in the Python scripts.

4. **Run the Jupyter Notebooks**:
    ```
    jupyter notebook
    ```
    Navigate to `little_lemon.ipynb` or `sales_report.ipynb` to view and run the code cells.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request if you'd like to add features or make modifications.

## License

This project is licensed under the terms of the [LICENSE](LICENSE) file included in the repository.


