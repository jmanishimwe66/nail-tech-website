# Nail Technician Website

A modern, mobile-first, single-page website for a nail technician. The website presents services, pricing, examples of nail designs, and clear ways for customers to book or make inquiries.

## Project Objectives

- Establish a professional online presence.
- Showcase nail services and previous work.
- Make service prices and business information easy to find.
- Encourage customers to book appointments or contact the technician.

## Key Features

- Hero section with a clear booking call to action.
- Services and pricing.
- Nail design gallery.
- About the technician.
- Customer testimonials, if available.
- Location and opening hours.
- WhatsApp, phone, and social media links.
- Simple booking inquiry form, if required.

## Technology Stack

- **Frontend:** React.js, TypeScript
- **Backend:** Python, FastAPI, only if custom backend functionality is required
- **Database:** Supabase PostgreSQL, if bookings or other persistent data must be stored
- **Authentication:** Supabase Auth, if required for protected features
- **Storage:** Supabase Storage, if dynamic gallery management is required
- **Containerization:** Docker and Docker Compose, if needed for the chosen deployment workflow

## Architecture

The initial version can be a lightweight React application with direct contact or WhatsApp booking links. FastAPI and database functionality should be introduced only if the agreed requirements need them.

## Getting Started

### Prerequisites

- Node.js and npm
- Python 3 if the backend is included
- Docker if containerization is configured
- A Supabase project if Supabase services are required

### Environment Configuration

Create environment files based on `.env.example`.

If Supabase is used in the frontend, configure:

- `VITE_SUPABASE_URL`
- `VITE_SUPABASE_ANON_KEY`

Backend variables should be configured only if a backend is included. Keep all privileged credentials server-side and out of version control.

### Development

Install frontend dependencies:

```bash
cd frontend
npm install
npm run dev
```

If a FastAPI backend is included, install its dependencies and start it using the configured application entry point.

If Docker is configured:

```bash
docker compose up --build
```

## Initial Scope

The first release focuses on a single page, services, pricing, a gallery, business information, and a simple booking or contact flow. Online scheduling, automated reminders, customer accounts, and deposits are excluded unless separately approved.

## Quality Assurance

Test responsive layouts, section navigation, gallery display, booking links, contact information, and accessibility basics.

## Project Status

In development.

## License

To be determined by the project owner.
