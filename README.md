Project Harmony: General Ledger App
Overview
Project Harmony is a modern, intuitive, and robust general ledger application designed to simplify accounting for small to medium-sized businesses. It provides a clear and accurate financial picture, helping you make informed decisions with confidence. This application is built with scalability and ease of use at its core.

Key Features
Double-Entry Accounting: Ensures financial integrity and accuracy by recording every transaction with corresponding debit and credit entries.

Chart of Accounts: A fully customizable chart of accounts to tailor the ledger to your specific business needs.

Journal Entries: Easily create, edit, and post journal entries for all business transactions.

Financial Reporting: Generate essential financial statements, including the Balance Sheet, Income Statement, and Statement of Cash Flows.

User-Friendly Interface: A clean and intuitive UI that makes navigating complex financial data straightforward.

Secure & Reliable: Built with security best practices to ensure your financial data is always safe.

API for Integration: A RESTful API to connect Project Harmony with other business tools and systems.

Tech Stack
Framework: Flask (Python)

Frontend: Jinja2 Templates with HTML, CSS, and JavaScript

Database: PostgreSQL

Authentication: Flask-Login or similar JWT library

Getting Started
Prerequisites
Make sure you have the following installed on your local development machine:

Python (v3.9 or later)

pip (Python package installer)

PostgreSQL

Installation
Clone the repository:

git clone https://github.com/slugboot1880/Project_Harmony
cd project-harmony

Create and activate a virtual environment:

# For Windows
python -m venv venv
.\venv\Scripts\activate

Install dependencies:

pip install -r requirements.txt

Set up your database:

Create a PostgreSQL database for the project.

Navigate to the project directory and copy the .env.example file to a new .env file:

cp .env.example .env

Update the .env file with your PostgreSQL database credentials. Your Flask config.py file should be configured to read from this file.

Run database migrations: (Assuming you are using Flask-Migrate)

flask db upgrade

Running the Application
Start the development server:

flask run

The application will be available at http://127.0.0.1:5000/.

Usage
After installation, you can navigate to http://127.0.0.1:5000/ in your browser.

Register a new user account.

Set up your company's Chart of Accounts.

Begin creating and posting journal entries for your business transactions.

Generate financial reports to view your company's performance.

Collaborating on Project Harmony
This project is set up for collaboration, and we welcome contributions! To ensure a smooth workflow for everyone, regardless of where they are in the world, please follow these guidelines.

Workflow
Pick an Issue: Go to the Issues tab on GitHub. Find an open issue you'd like to work on and assign it to yourself, or create a new one if you have a new idea. This prevents multiple people from working on the same thing.

Create a Branch: Create a new branch from the main branch for your feature or bug fix. Use a descriptive name.

git checkout -b feature/user-authentication

Code & Commit: Make your changes and commit them with clear, descriptive messages. Reference the issue number in your commits (e.g., git commit -m "feat: Add password reset form. Closes #12").

Create a Pull Request: Push your branch to the repository and open a Pull Request (PR) to merge your branch into main. In the PR description, explain the changes you made.

Code Review: At least one other person should review the PR. This is a great opportunity to learn, share knowledge, and catch bugs before they get into the main codebase. Once approved, the PR can be merged.

Communication
GitHub Issues: For discussing specific tasks, features, or bugs.

Discord/Slack: Set up a dedicated channel for the project for real-time discussions, questions, and team coordination.
