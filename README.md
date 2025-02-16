**Job Portal Development**

Overview
This project is a job portal built on ASP.NET Core MVC. The platform connects employers and job seekers, facilitating job postings and simplifying the job search process. The project supports CRUD (Create, Read, Update, Delete) operations.
Features

Main Pages:
- About: General information about the website.

- Contact: Telephone and email details.

- Register & Sign In: User registration and authentication.

- Job Listings: Page displaying available job postings.

- Admin Panel: A panel for site administrators to manage job postings, categories, and users.

**CRUD Operations:**

Create: Adding new job postings and categories.

Read: Retrieving job and category details (title, salary, location, job requirements, etc.).

Update: Updating existing job postings and category details.

Delete: Removing job postings and categories.

User Management:

User registration and profile creation for job seekers.

Moderation of job postings through the admin panel.

**Data Model**

The project includes the following job and category data fields:

Job Title: The name of the job position.

Salary: The proposed salary.

Description: Job requirements and additional details.

Category Name: The category of the job listing.

API Endpoints

The project includes the following API endpoints:

GET /jobs: Retrieves a list of all job postings.

GET /jobs/{id}: Retrieves details of a specific job posting.

POST /jobs: Adds a new job posting.

PUT /jobs/{id}: Updates an existing job posting.

DELETE /jobs/{id}: Deletes a job posting from the database.

GET /categories: Retrieves a list of all categories.

POST /categories: Adds a new category.

DELETE /categories/{id}: Deletes a category.

Technologies

Backend: ASP.NET Core MVC, Entity Framework Core

Frontend: HTML, CSS, JavaScript, Bootstrap

Database: Microsoft SQL Server

Authentication: Identity Framework (Email confirmation, password reset system)

