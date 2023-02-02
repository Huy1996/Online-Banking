# Banking Web Application

## Overview
A secure and user-friendly web application that allows users to manage their banking activities.
The application includes features such as account management, transaction history, and bill payments.

## Technologies Stack

### Backend (Python):
* Flask, a Python web framework
* PostgreSQL, an open-source relational database management system
* SQL-Alchemy, a Python SQL toolkit and ORM library that facilitates communication between
Python and relational database like PostgresSQL

### Frontend (JavaScript):
* React, a JavaScipt library for building user interface
* Redux, a state management library for JavaScript applications, used in conjunction to efficiently manage
and update components in complex applications


__The entire applicaiton is containerized using Docker for easy deployment and management__

## Features
* User account management: Allows users to create, manage, and close their accounts
* Transactino history: Allow users to view and track their past transactions
* Secure user authentication: Implements secure authentication mechanisms to ensure user privacy and security

## How to Setup and Run
1. Clone the repository to your local machine <br>
> `git clone --recursive git@github.com:Huy1996/Online-Banking.git`
2. Navigate to the project directory
> `cd Online-Banking`
3. Build the Docker containers.
> `docker-compose build`
4. Start the containers.
> `docker-conpose up`
5. Access the frontend at `http://localhost:3000`.

Note: To be able to run this app, you need to add `.env` file in the Banking-API
directory. Below is the requirement variable needed for the env file

> JWT_SECRET_KEY <br>
> SQLALCHEMY_DATABASE_URI <br>
> AWS_ACCESS_KEY_ID <br>
> AWS_SECRET_ACCESS_KEY <br>
> S3_BUCKET_NAME <br>
> S3_REGION <br>
