# bike-shop
an interactive Bash program that stores rental information for your bike rental shop using PostgreSQL.


---

# Bike Rental Shop

This Bash script simulates a bike rental shop where users can rent and return bikes. The script interacts with a PostgreSQL database to manage bike rentals and customer information.

## Getting Started

### Prerequisites

- Bash environment
- PostgreSQL installed
- Access to a PostgreSQL database named `bikes`
- Necessary permissions to run PostgreSQL commands

### Setup

1. Clone or download the project repository.
2. Ensure PostgreSQL is running.
3. Modify the `psql` command in the script to match your PostgreSQL configuration.
4. Ensure the database schema matches the expected structure (customers, bikes, rentals).

### Running the Script

Run the script `bike-shop.sh` in a Bash terminal:

```bash
./bike-shop.sh
```

Follow the on-screen prompts to navigate the bike rental shop menu and interact with the system.

## Functionality

- **Rent a Bike**: View available bikes, select a bike to rent, provide customer information, and confirm the rental.
- **Return a Bike**: Enter the customer's phone number, select the bike to return, and confirm the return.
- **Exit**: Terminate the script and exit the bike rental shop.

## Database Schema

The script interacts with the following tables in the `bikes` database:

- **customers**: Contains customer information (phone, name).
- **bikes**: Stores bike details (bike_id, type, size, available).
- **rentals**: Tracks bike rentals (customer_id, bike_id, date_returned).

## Notes

- The script assumes a basic database structure and access rights. Adjustments might be needed for different environments or database configurations.
- Ensure proper error handling and validation in a production scenario.
- The script might need additional configurations or adaptations based on specific database setups or user requirements.

## Author

Frank Hodges




