# Loan Management System

The Loan Management System is a web application that allows you to manage loans of books to customers. It provides features to create new loans, track active loans, and monitor overdue loans.

## Features

- Create new loans by selecting a customer and a book.
- Track active loans and display relevant information such as customer name, book name, loan date, and loan duration.
- Highlight overdue loans in the active loans list.
- Automatically update the loan status every 5 seconds to reflect changes in loan data.
- Prevent loan creation if the selected book is already on loan.
- Retrieve all loan records from the database and display them in the "All loans" table.

## Technologies Used

- Python
- Flask (Python web framework)
- SQLAlchemy (Python SQL toolkit and Object-Relational Mapping)
- JavaScript
- Axios (JavaScript HTTP client)
- HTML
- CSS

## Contributing

Contributions to the Loan Management System are welcome! If you find a bug or have suggestions for improvements, please open an issue or submit a pull request.

When contributing to this repository, please first discuss the change you wish to make via issue or email before making a pull request.

### Prerequisites

- Python (version 3.6 or higher)
- Flask (installation instructions can be found [here](https://flask.palletsprojects.com/en/2.0.x/installation/))
- SQLAlchemy (installation instructions can be found [here](https://docs.sqlalchemy.org/en/14/intro.html#installation))
- Node.js (version 12 or higher) and npm (Node.js package manager)
