---
sidebar_position: 1
---

# Installation Guide

:::warning
The OSSC is currently under active development and has not been officially released. 
The `main` branch represents the latest version, but please note:

- There is no guaranteed stability at this stage.
- It is not recommended to use OSSC in production environments yet.

We appreciate your interest and encourage you to follow the development progress.
:::

## Local Installation

### Prerequisites

To set up OSSC locally, you'll need a PHP environment. We recommend using [Laravel Herd](https://herd.laravel.com/), a user-friendly tool that simplifies the process of creating a local PHP server.

### Clone the Repository
```bash
git clone https://github.com/tecsteps/ossc.git
```

### Run the application
```bash
cd ossc
composer run dev
```

### Access the Application

The application should now be accessible at [http://localhost:8000](http://localhost:8000). Locally the application is using a SQLite database, which is located at `database/database.sqlite`. 

The OSSC has two types of users: **marketplace owners** and **sellers**.
* Onwer login [/owner](http://localhost:8000/owner) with `owner@ossc.tech` as username and password
* Seller registration [/seller/register](http://localhost:8000/seller/register). To access the seller panel, you need to register a seller account first.