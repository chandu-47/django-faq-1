# Django FAQ Management System

## Project Overview
This project is a Django-based FAQ management system that allows users to manage and interact with frequently asked questions (FAQs) in multiple languages. It includes features such as WYSIWYG editor support, REST API for managing FAQs, and integration with Google Translate for real-time translations.

## Features
- Multilingual FAQ management.
- WYSIWYG (What You See Is What You Get) editor for content creation.
- REST API to interact with FAQs.
- Integration with Google Translate for automatic translations.
- Caching with Redis for improved performance.
- Unit tests for backend functionality.
- Dockerized environment for easy deployment.

## Installation

### Prerequisites
- Python 3.x
- Django 4.x or higher
- Redis (for caching)
- Docker (for containerized deployment)

### Setup Instructions
1. Clone the repository:

2. Create a virtual environment:

3. Install the required dependencies:

4. Configure your environment variables (e.g., for Google Translate API, Redis):
- Create a `.env` file and add necessary variables such as:
  ```
  GOOGLE_TRANSLATE_API_KEY=your_google_translate_api_key
  REDIS_URL=redis://localhost:6379/0
  ```

5. Run migrations to set up the database:

6. Run the development server:

7. Visit `http://127.0.0.1:8000/` in your browser to view the application.

## Running Tests
To run the unit tests for this project, use the following command:

## Docker Deployment (Optional)
1. Build and run the Docker container:
