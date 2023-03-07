# Authentication and Authorization exercise

This is an exercise with solution of an API server build on Postgres and NodeJS. The purpose of this exercise is to show how to implement a simple server to help authenticate user using username and password and provide JWTs as authorization method.

## Installation
1. Clone repo to your local machine
    ```
    git clone https://github.com/VicaSpace/athen-books.git
    ```
2. Install needed packages
- Using npm:
    ```
    npm install
    ```
- Using yarn:
    ```
    yarn
    ```
3. Set up **.env** file for enviroment variables
- Make a copy of **.env.example** and named it **.env**
- Modify username, password and database name for postgres server:
    ```
    DATABASE_URL="postgresql://postgres_user:postgres_password@127.0.0.1:5432/postgres_database?schema=public"
    ```
4. Run server
- Using npm:
    ```
    npm run dev
    ```
- Using yarn:
    ```
    yarn dev
    ```

## Requirement
- [Swagger](https://app.swaggerhub.com/apis-docs/thienanh313/code_academy_4_auth/1.0.0)
- Solution:
    ```
    git checkout solution
    ```

## Run tests
Tests are already created. Run tests to test you APIs behavior.
1. Run tests
   - Using npm:
    ```
    npm run test
    ```
   - Using yarn:
    ```
    yarn test
    ```
2. Run tests with coverage
   - Using npm:
    ```
    npm run test:coverage
    ```
   - Using yarn:
    ```
    yarn test:coverage
    ```

## Author
Vu Thi Thien Anh
Vu_Thien_Anh@mckinsey.com