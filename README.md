HNG12 Stage 0 - Public API

Project Description

This is a simple public API developed for HNG12 Stage 0. The API returns basic information in JSON format, including:

The registered email address.

The current datetime in ISO 8601 format (UTC).

The GitHub repository URL.

Technology Stack

Programming Language: Python

Framework: Flask

Deployment: To be deployed on a publicly accessible platform

CORS Handling: Handled properly for cross-origin requests

API Specification

Endpoint

GET /

Response Format (200 OK)

{
  "email": "isidoreuyaiabasi@gmail.com",
  "current_datetime": "2025-01-30T09:30:00Z",
  "github_url": "https://github.com/Uyai-Abasi/HNG12-Stage-0.git"
}

Project Structure

HNG12-Stage-0/
│── app.py            # Main application file
│── main.py           # 
│── requirements.txt  # List of dependencies
│── .gitignore        # Git ignore file
│── venv/             # Virtual environment folder

Setup Instructions

Prerequisites

Ensure you have the following installed:

Python 3.10+

pip (Python package manager)

Installation Steps

Clone the repository:

git clone https://github.com/Uyai-Abasi/HNG12-Stage-0.git
cd HNG12-Stage-0

Create and activate a virtual environment:

python -m venv venv
source venv/bin/activate   # On macOS/Linux
venv\Scripts\activate      # On Windows

Install dependencies:

pip install -r requirements.txt

Run the API:

python app.py

Deployment

The API is required to be deployed to a publicly accessible endpoint. Consider using services like:

Render

Vercel

Railway

Heroku

Example Usage

You can test the API locally by opening a browser or using curl:

curl -X GET http://127.0.0.1:5000/

Or using Postman/Insomnia.
