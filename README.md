![example workflow](https://github.com/fergueiredo/excon-api/actions/workflows/build.yml/badge.svg)

# ExCon - Expenses Controller

Welcome to Expense Controller API repository! This api is designed to help users manage their personal finances efficiently and effectively.

## Features

- [ ] **Expense and Income Tracking:** The API provides endpoints to allow users to create and manage their financial 
transactions. Users can send POST requests to the `/transactions` endpoint with JSON payloads containing transaction 
details such as amount, category, and description. The API stores this information in the database and allows users 
to retrieve, update, and delete transactions as needed.
- [ ] **Category Management:** Users can categorize their transactions for better organization and analysis. The API 
provides endpoints for managing transaction categories, including creating new categories, updating existing 
categories, and deleting categories. Users can send POST, PUT, and DELETE requests to the `/categories` endpoint with 
JSON payloads containing category details.
- [ ] **Detailed Reports:** The API offers endpoints to generate detailed reports and insights into users' spending 
habits. These endpoints analyze transaction data stored in the database and generate reports in JSON or other suitable 
formats. Users can send GET requests to the `/reports` endpoint with parameters specifying the desired time range, 
categories, or other criteria for the report.

## Installation

1. Clone the repository to your local machine.
2. Open the project in your favorite IDE or editor.
3. Configure the application properties such as database connection strings and security settings.
4. Build the project using Maven: `mvn clean install`.
5. Run the application using your IDE or the command line: `mvn spring-boot:run`.

## Endpoints

### Wallets
- [ ] **POST /wallets:** Create a new wallet.
- [ ] **GET /wallets:** Retrieve a list of wallets.
- [ ] **GET /wallets/{id}:** Retrieve a specific wallet by ID.
- [ ] **PUT /wallets/{id}:** Update a specific wallet.
- [ ] **DELETE /wallets/{id}:** Delete a specific wallet.

### Transactions
- [ ] **POST /transactions:** Create a new transaction.
- [ ] **GET /transactions:** Retrieve a list of transactions.
- [ ] **GET /transactions/{id}:** Retrieve a specific transaction by ID.
- [ ] **PUT /transactions/{id}:** Update a specific transaction.
- [ ] **DELETE /transactions/{id}:** Delete a specific transaction.

### Categories
- [ ] **POST /categories:** Create a new category.
- [ ] **GET /categories:** Retrieve a list of categories.
- [ ] **GET /categories/{id}:** Retrieve a specific category by ID.
- [ ] **PUT /categories/{id}:** Update a specific category.
- [ ] **DELETE /categories/{id}:** Delete a specific category.

### Reports
- tbd

## Contributing

We welcome contributions from the community! If you have ideas for new features or improvements, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

If you have any questions, please feel free to leave a comment.
