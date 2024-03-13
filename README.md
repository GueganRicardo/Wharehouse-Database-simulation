# Wharehouse-Database-simulation

## Authors
- Bruno Eduardo Machado Sequeira
- Ricardo Rafael Ferreira Guegan

## User Manual

### Prerequisites:
- **Postman**: Required for propper testing of the API.
- **Python**: Necessary to run the program along with several libraries for proper functioning.

### Required Libraries:
- Flask – 2.1.1
- Flask-RESTful – 0.3.9
- PyJWT – 2.3.0
- psycopg2 – 2.9.3

### Database Setup:
1. Open the provided folder and execute the commands in the command line.
2. Log in with the password set during the PostgreSQL installation.
3. Execute the commands to create the database and a new user.
4. Close the console, reopen it, and log in with the newly created user credentials.
5. Execute the scripts `criaTabelas.sql` and `FuncoesSQL.sql` to set up the tables and triggers.

### Running the Program:
1. In the executable, input the function name "API_RED.py", the username, host (127.0.0.1), port (5432), and the database name.

### Authentication:
- **Login**: Use the `LOGIN` endpoint with `username` and `password` parameters to receive a token.

### Endpoints:
- **Add Products**: `ADD_PRODUTOS` endpoint to list a product for sale.
- **Update Product**: `UPDATE_PRODUTO` endpoint to update product details.
- **Make Purchase**: `REALIZA_COMPRA` endpoint to perform a purchase.
- **Product Info**: `INFO_PRODUTO` endpoint to get updated product information.
- **User Info**: `INFO_UTILIZADORES` endpoint for admin to view user information.
- **Rating**: `RATING` endpoint to rate a purchased product.
- **Question**: `PERGUNTA` endpoint to ask questions about a product.
- **Answer**: `RESPOSTA` endpoint to answer questions about a product.
- **Statistics**: `ESTATÍSTICAS` endpoint for admin to retrieve sales statistics.
- **Product Details**: `INFORMAÇÃO_PRODUTO` endpoint to get generic product details.

## ER Diagrams and Physical Diagrams:
- Provided within the project documentation.
