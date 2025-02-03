# Django FAQ Management System

A Django-based FAQ management system with multilingual support, a WYSIWYG editor for content formatting, caching for optimized performance, and a REST API for integration.

---

## Features
- **FAQ Management:** Add, update, and delete FAQs using a user-friendly admin panel.
- **WYSIWYG Editor:** Supports rich text formatting for FAQ answers using CKEditor.
- **Multilingual Support:** Store and retrieve FAQs in multiple languages (e.g., English, Hindi, Bengali).
- **REST API:** Fetch FAQs via a language-specific query parameter (`?lang=`).
- **Automated Translations:** Leverages Google Translate API for dynamic translations.
- **Redis Caching:** Improves API performance by caching translated data.
- **Docker Support:** Dockerized for easy deployment.

---

## Installation

### 1. Clone the Repository
```bash
git clone https://github.com/chandu-47/django-faq-1.git
cd django-faq-1
