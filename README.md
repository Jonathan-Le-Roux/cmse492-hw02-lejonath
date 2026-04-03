# Movie Rental Store  

## Overview

This project analyzes a movie rental database using the Sakila database to generate a manager-ready report on movie profitability based on age ratings.

The goal is to identify which categories of films (e.g., PG, PG-13, R) as well as which films generate the most revenue and provide insights that could inform business decisions such as inventory management, marketing focus, and pricing strategies.

## 📂 Project Structure
```
hw02-lejonath/
│── .gitignore            # Files ignored by Git
│── docker-compose.yml    # Docker configuration for Sakila Database
│── HW02-STUDENT.ipynb    # Main notebook for the assignment
│── README.md             # Project documentation
│── requirements.txt      # used for reproducibility by venv
```

## Environment set up

### Installations
---
#### Python

This project uses python 3.12.2. You can install this or a later version of python at: https://www.python.org/downloads/

---
#### Docker

If you already have Docker Desktop installed, you can skip this section.

Follow the instructions that match your operating system:

- **Windows:**
  - Go to the official [Docker Desktop](https://www.docker.com/products/docker-desktop/) download page and locate the Windows installer appropriate for your system.
  - Download and run the installer.
  - Accept the default options unless you have a specific reason not to.
  - If prompted about WSL2, accept the recommended settings.

- **macOS:**
  - Go to the official [Docker Desktop](https://www.docker.com/products/docker-desktop/) download page and locate the macOS installer.
  - Choose the installer that matches your hardware (Intel vs Apple Silicon).
  - Download and run the installer, then follow the on-screen instructions.

---
To ensure installation use the following command in the terminal:

```bash
docker --version
```
You should see something in the form of :
 - Docker version 29.X.X build XXXXXX

---
### Setup

Create a folder to run the project with the name hw02-lejonath

Clone the repository:
```bash
cd hw02-lejonath
git clone https://github.com/Jonathan-Le-Roux/cmse492-hw02-lejonath/tree/main
```

**Note:** Ensure you are in the project root directory.

To set up the virtual environement run the following in the terminal:

```bash
# Create the virtual environemt
python3.12 -m venv .venv

# To activate the virtual environment choose: 
source .venv/bin/activate       # on Mac/Linux
source .venv\Scripts\activate   # on Windows

# Then install the correct dependencies: 
pip install -r requirements.txt
```
To set up the database through sakila run the following in the terminal:

```bash
docker compose up -d
```

## Running the SQL queries

Open HW02-Student.ipynb.

Ensure that the virtual environment is active and ensure that it is being used as the kernel for the notebook. 


## Skills Showcased

- SQL: JOINS
- SQL: CTE's
- SQL: Window Queries
- SQL: Validation of Results
- Git
- Reproducibility

