# Spring Boot Bank Accounts using Dockerfile and Docker Compose

This project provides a robust API for managing bank accounts, enabling functionalities such as account creation, balance inquiries, and transactions. It allows users to create new accounts, retrieve account details, and perform deposits and withdrawals. This API enhances the efficiency of banking operations by providing real-time access to account information, ensuring seamless transaction processing, and improving customer satisfaction through transparent and accessible financial services.

## Project Status

This project is currently in development and is being worked on for version 1.0.0.

## Technologies Used

- Java 17
- Spring Boot
- Maven
- MySQL
- Spring Data JPA
- Docker

## Installation and Setup

1. Clone this repository to your local machine using the following command:
    ```bash
    git clone https://github.com/Agustin199811/spring-docker-bank.git

2. Import the project into your preferred IDE (e.g., IntelliJ IDEA or Eclipse) as a Maven project.

3. Run the Spring Boot application. The application will be available at `http://localhost:8082`.
    - Navigate to the root directory of your project (where your docker-compose.yml file is located).
        - `Build the Docker Compose`:
            + docker-compose build
        - `Run the Docker container:`
            + docker-compose up

## Usage


The Accounts REST API exposes the following endpoints:

- `GET /api/accounts`: Retrieve all accounts.
- `GET /api/accounts/{id}`: Retrieve an account by ID.
- `POST /api/accounts`: Create a new account.
- `PUT /api/accounts/{id}/deposit`: Deposit money into an account.
- `PUT /api/accounts/{id}/withdraw`: Withdraw money from an account.

You can use tools such as Postman or cURL to send HTTP requests to these endpoints.

## Deploy on Render

Switch to the `deploy` branch to upload to the Render cloud provider

To deploy the application on the Render cloud provider, follow these steps:

1. **Switch to the `deploy` branch**:
   ```bash
   git checkout deploy
## AWS with EC2
![image](https://github.com/Agustin199811/spring-docker-bank/assets/91472854/e7f4c4a8-ceb4-4e97-990f-e3403fe9c2c3)

![image](https://github.com/Agustin199811/spring-docker-bank/assets/91472854/4e4e949f-773e-4be1-9b54-6c3eb2c6ffe7)

![image](https://github.com/Agustin199811/spring-docker-bank/assets/91472854/502466f0-f051-4a05-bbcb-1ff655a6e69b)

![image](https://github.com/Agustin199811/spring-docker-bank/assets/91472854/c17a72eb-09f9-4197-ade6-62cb063c9f6e)

![image](https://github.com/Agustin199811/spring-docker-bank/assets/91472854/7bf68f67-4308-4dfa-b01c-b6e611a471d5)

![image](https://github.com/Agustin199811/spring-docker-bank/assets/91472854/543265b7-24d0-485f-b84a-21fe52203118)

![image](https://github.com/Agustin199811/spring-docker-bank/assets/91472854/8e9572f8-5431-4fde-9434-be084f7880c6)

## Contribution

If you wish to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix: `git checkout -b my-new-feature`.
3. Make your changes and commit them: `git commit -am 'Add a new feature'`.
4. Push your changes to your forked repository: `git push origin my-new-feature`.
5. Create a new pull request and describe your changes in detail.

## License

This project is licensed under the MIT License. You can find more information in the `LICENSE` file.

## Contact
Authors: Toapanta Agustin; Llano Edison

If you have any questions or suggestions, feel free to contact the development team at (toapantaagustin9c@gmail.com).
