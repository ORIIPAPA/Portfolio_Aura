# Aura Dominic - Portfolio

![GitHub-style Portfolio](screenshot.png)

🔗 **Live Site:** [https://aurad-portfolio.netlify.app/#projects](https://aurad-portfolio.netlify.app/#projects)

## Features
- Real-time data from Firebase Firestore
- Responsive GitHub-inspired design
- Contact form with database storage
- Dynamic content loading
- Analytics integration

## Technology Stack
- Frontend: HTML5, CSS3, JavaScript
- Database: Firebase Firestore
- Hosting: Netlify
- CI/CD: Netlify CLI

## Setup Instructions

1. Clone the repository
2. Create Firebase project and enable Firestore
3. Set environment variables in Netlify:
   - `FIREBASE_API_KEY`
   - `FIREBASE_AUTH_DOMAIN`
   - `FIREBASE_PROJECT_ID`
   - etc.
4. Deploy to Netlify

## Database Structure

### Collections:
- `skills` { name: string, icon: string, order: number }
- `projects` { title: string, description: string, tech: array, link: string, published: boolean, date: timestamp }
- `contacts` { name: string, email: string, subject: string, message: string, timestamp: timestamp, status: string }
