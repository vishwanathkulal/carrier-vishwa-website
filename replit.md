# Carrier Vishwa Website

## Overview
A professional Flask-based website for Carrier Vishwa - a platform dedicated to career guidance, skill development, and job placement assistance.

## Current State
- **Status**: Fully functional and ready for use
- **Framework**: Flask 3.0.0 with Python 3.11
- **Deployment**: Configured for Replit autoscale deployment
- **Port**: 5000 (configured for Replit environment)

## Project Architecture
- `app.py` - Main Flask application with routes
- `templates/` - HTML templates using Jinja2
  - `base.html` - Base template with navigation and footer
  - `index.html` - Homepage with hero section and features
  - `about.html` - About page with mission and vision
- `static/css/` - Stylesheets
  - `style.css` - Main stylesheet with responsive design
- `requirements.txt` - Python dependencies

## Recent Changes (September 02, 2025)
- ✅ Set up complete Flask application structure
- ✅ Created responsive website with professional design
- ✅ Configured for Replit environment (0.0.0.0:5000)
- ✅ Set up development workflow
- ✅ Configured deployment with gunicorn
- ✅ Added navigation between Home and About pages

## Development Setup
- **Development Server**: Flask development server on port 5000
- **Production Server**: Gunicorn WSGI server
- **Environment**: Configured to allow all hosts for Replit proxy

## Deployment Configuration
- **Target**: Autoscale (stateless website)
- **Command**: `gunicorn --bind=0.0.0.0:5000 --reuse-port app:app`
- **Port**: 5000

## User Preferences
- Professional, clean design
- Responsive layout for mobile and desktop
- Career-focused content and messaging