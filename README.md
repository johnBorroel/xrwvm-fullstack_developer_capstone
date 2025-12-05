# Fullstack Developer Capstone

Welcome to the **Fullstack Developer Capstone** project! This repository is the culminating project for fullstack developer training, demonstrating both frontend and backend web technologies plus deployment practices.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [License](#license)

## Project Overview

This project is a mockup web application for a car dealership network, built to showcase fullstack development skills and real-world user experiences. Key capabilities and use cases include:

- **Car Dealership Listings:** Users can browse a list of dealerships and navigate to detail pages for each one.
- **Review Submission:** Visitors can submit reviews for specific dealerships, enabling user interaction and feedback.
- **IBM Sentiment Analyzer Integration:** User-submitted reviews are automatically analyzed using IBM's sentiment analyzer. The detected tones for each review are visually represented (e.g., color-coded or icon-indicated) on the dealership detail pages, helping other users quickly gauge feedback sentiment.
- **Dedicated Pages:**
  - **About Us:** Shares information about the business or organization behind the dealerships.
  - **Contact Page:** Allows users to send inquiries or contact the dealership network for more information.
- **Responsive and Modern UI:** All pages are designed to look and work well across devices, providing a clean, intuitive user experience.

This capstone illustrates how to integrate external APIs (for sentiment analysis), manage dynamic content and navigation, and create interactive, user-focused features typical of professional web solutions.

## Features

- Car dealership directory and dealership detail pages
- User review submission and dynamic display
- IBM sentiment analysis for user reviews with visual tone highlights
- Responsive frontend UI
- About Us and Contact pages
- RESTful backend API with authentication and CRUD
- Docker-based development
- Modular codebase for scalability
- Basic test suite

## Tech Stack

- **Backend:**
  - Python with Django (main application, REST APIs)
  - Node.js with Express.js (data serving for dealerships and reviews)
- **Frontend:**
  - React
  - HTML & CSS for static pages and styling
  - Bootstrap (styling and layout)
- **Containerization:** Docker
- **Others:** Shell scripts for automation

> **Language composition:**
> - JavaScript: 45.5%
> - Python: 27.6%
> - HTML: 13.9%
> - CSS: 11.2%
> - Dockerfile: 1.5%
> - Shell: 0.3%

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/)
- [Python 3.8+](https://www.python.org/)
- [Docker](https://www.docker.com/)

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/johnBorroel/xrwvm-fullstack_developer_capstone.git
   cd xrwvm-fullstack_developer_capstone
   ```

2. **Install backend dependencies:**

   ```bash
   cd backend
   pip install -r requirements.txt
   ```

3. **Install frontend dependencies:**

   ```bash
   cd ../frontend
   npm install
   ```

## Project Structure

```
├── backend/         # Python backend (Flask/Django/FastAPI)
├── frontend/        # Frontend (React/Vue/HTML/JS)
├── docker/          # Dockerfiles and scripts
├── README.md
├── .gitignore
```

## License

This project is licensed under the MIT License.

---

_This repository is maintained by [johnBorroel](https://github.com/johnBorroel)._
