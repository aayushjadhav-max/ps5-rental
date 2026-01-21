# PS5 Rental Website - Static HTML Version

## Overview
A frontend-only rental website for PlayStation 5 consoles, games, and controllers built with pure HTML, CSS, and JavaScript. Features rental cost calculation and form interactions without backend connectivity.

## Technical Requirements
- Pure HTML, CSS, and JavaScript implementation (no React or backend)
- Shared `style.css` file for design consistency
- Shared `script.js` file for interactive functionality
- Responsive design with PS5 brand colors (blue and white tones)
- Content language: English

## Analytics Integration
- Google Analytics tracking code (G-YR9GR62G68) must be included immediately after the `<head>` element on all pages
- Single instance per page across Home, About, Contact, and Rentals pages

## Site Structure
- Consistent navigation bar linking all four pages
- Footer with basic information on all pages
- Clean, responsive layout aligned with PS5 branding

## Pages

### Home Page
- Hero section showcasing PS5 rental services using gaming setup hero image
- Featured rental categories section displaying:
  - PS5 Consoles (with console image)
  - Games (with games image)
  - Controllers (with controllers image)
- Each category shows attractive visuals and brief descriptions
- Navigation to other pages

### About Page
- Description of rental services
- Company mission statement
- Rental policies and terms
- Service area information

### Contact Page
- Contact form with fields:
  - Name (required)
  - Email (required)
  - Message (required)
- Contact details display:
  - Phone number
  - Email address
  - Business address
- Form submission shows confirmation message (no backend submission)

### Rentals Page
- Item selection interface with three categories using provided images:
  - PS5 Consoles
  - Games
  - Controllers
- Rental form with fields:
  - Item type selection dropdown
  - Quantity selector
  - Number of rental days input
- Real-time cost calculation display using JavaScript
- Form submission shows:
  - Total rental cost breakdown
  - Confirmation message
  - Instructions to contact manually for final booking

## JavaScript Functionality
- Dynamic rental cost calculation based on item type, quantity, and duration
- Form validation and submission handling
- Interactive elements and user feedback
- No backend API calls or data persistence
