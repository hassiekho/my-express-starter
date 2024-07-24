# My Express App

An Express.js project with TypeScript, Prisma, and modern tools.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Scripts](#scripts)
- [Folder Structure](#folder-structure)
- [License](#license)

## Introduction

This is a boilerplate project for building a modern web application using Express.js, TypeScript, and Prisma. It includes a ready-to-use setup for rapid development and deployment.

## Features

- **Express.js**: Fast, unopinionated, minimalist web framework for Node.js.
- **TypeScript**: TypeScript is a strongly typed programming language that builds on JavaScript, giving you better tooling at any scale.
- **Prisma**: Next-generation ORM for Node.js and TypeScript.
- **Nodemon**: Utility that will monitor for any changes in your source and automatically restart your server.
- **Dotenv**: Loads environment variables from a `.env` file into `process.env`.

## Installation

1. Clone the repository:

    ```
    git clone https://github.com/yourusername/my-express-app.git
    cd my-express-app
    ```

2. Install dependencies:

    ```
    npm install
    ```

3. Set up Prisma:

    ```
    npx prisma init
    ```

4. Configure your database connection in `prisma/.env`.

5. Generate Prisma client:

    ```
    npx prisma generate
    ```

## Usage

### Development Server

To start the development server with hot reloading:

```
npm run dev
```
