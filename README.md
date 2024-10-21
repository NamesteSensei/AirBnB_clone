# AirBnB Clone - MySQL

### Project Overview

This project is part of a series of projects aimed at building a simplified clone of the AirBnB platform. It uses **Python**, **SQLAlchemy**, and **MySQL** to store and manage the backend, with an emphasis on object-relational mapping (ORM). The goal is to create a functional storage system that can handle both file-based and database-based storage.

---

## Table of Contents

- [Project Overview](#project-overview)
- [Requirements](#requirements)
- [Environment Variables](#environment-variables)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Testing](#testing)
- [Authors](#authors)
- [Team Information](#team-information)

---

## Requirements

### Python Scripts

- All files will be interpreted/compiled on **Ubuntu 20.04 LTS** using **Python 3.8.5**.
- Your code must follow the **PEP8** style guidelines.
- All modules should have documentation.
- All functions/classes should have appropriate docstrings.

### SQL Scripts

- All SQL files should be executed on **MySQL 8.0**.
- SQL scripts must follow best practices in terms of comments and structure.
- SQL keywords (e.g., SELECT, WHERE) should be in uppercase.

---

## Environment Variables

This project uses environment variables to configure the database and storage system.

- **HBNB_ENV**: The running environment (`dev` or `test`).
- **HBNB_MYSQL_USER**: The MySQL username.
- **HBNB_MYSQL_PWD**: The MySQL password.
- **HBNB_MYSQL_HOST**: The MySQL hostname (e.g., localhost).
- **HBNB_MYSQL_DB**: The name of the MySQL database.
- **HBNB_TYPE_STORAGE**: Storage type: `file` (FileStorage) or `db` (DBStorage).

---

## Technologies Used

- **Languages**: Python, SQL
- **Database**: MySQL
- **ORM**: SQLAlchemy
- **Testing**: Unittest
- **Version Control**: Git
- **Operating System**: Ubuntu 20.04 LTS

---

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/AirBnB_clone_v2.git
cd AirBnB_clone_v2
