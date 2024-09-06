# readme-book-exchange-app

### AN OVERALL GUIDE OF HOW TO SETUP THE BOOK EXCHANGE APPLICATION INTO YOUR LOCAL MACHINE

## Table of Contents
- [Installation](#installation)
- [environment variables](#env)
- [Running the project](#running)


## Installation

#### 1: Clone the frontend's repository:
```bash
git clone https://github.com/riteshshukladev/Book-exchange-application--client-.git
```
**Initialize the project in your local maching and run this specific commands**
```bash
npm install
```

#### 2: Clone the Backend's repository
```bash
git clone https://github.com/riteshshukladev/Book-exchange-application-backend.git
```
**Initialize the project in your local maching and run this specific commands**
```bash
npm install
```


## environment variables

 **First Create .env file in both the frontend and backend directory**

#### 1: .env for frontend :- 
 - VITE_API_URL=http://localhost:3008

#### 2 .env for backend :- 

- PORT = 3008
- DATABASE_URL=postgresql://main_owner:ifZ59vKxDmnS@ep-divine-butterfly-a1z43y16.ap-southeast-1.aws.neon.tech/main?sslmode=require
- JWT_SECRET=046d558926f3123a0214be55e0a322ff6ece80c43b757a43a9ad45ab1f5ab9700a5ebf82093c90fcf0f9896a0d5d90d07d486c2b3168608a905a8025370ec3ae

## Running the project

#### 1. Start the development server of the frontend of the application
```bash
npm run dev
```

#### 2. Start the development server of the backend of the application
```bash
node .\index.js
```




