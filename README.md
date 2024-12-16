# Power BI Dashboard with User Authentication

This project is a web application built using **Flask** that integrates a user authentication system (Login and Register) and provides access to an embedded **Power BI** dashboard. Users can register, log in, and view the Power BI report after authentication.

## Features

- **User Authentication**: 
  - Allows users to **register** and **log in**.
  - Passwords are hashed using `bcrypt` for secure storage.
  - User sessions are managed using Flask's session system.
  
- **Power BI Dashboard**: 
  - Once logged in, users are redirected to a page that shows a **Power BI** dashboard embedded in the web page.
  - The dashboard is embedded using Power BI's **Embed URL**.
  
- **Responsive Design**: 
  - The web application has a responsive layout using **CSS** to ensure a smooth user experience on both desktop and mobile devices.

## Tech Stack

- **Backend**: Flask (Python web framework)
- **Database**: SQLite (for storing user credentials)
- **Authentication**: Flask-Session, Flask-Bcrypt
- **Frontend**: HTML, CSS
- **Embedding**: Power BI (using Embed URL)

## Setup Instructions

Follow these steps to set up and run the application locally on your machine.

### Prerequisites

Make sure you have **Python** installed on your system. You can download it from [python.org](https://www.python.org/downloads/).

You will also need to install the following Python packages:

- Flask
- Flask-SQLAlchemy
- Flask-Bcrypt

### 1. Clone the Repository

Clone this repository to your local machine:

```bash
git clone https://github.com/your-username/your-repository-name.git
cd your-repository-name
