# Brew Admin Portal
A Single Page Application (SPA) designed for e-commerce administrators to manage coffee inventory. This project demonstrates proficiency in Advanced React, client-side routing, and CRUD operations using a simulated backend.

# Features
Landing Page: A welcoming dashboard providing an overview of the store.

Inventory Management: A dynamic list of products fetched from a db.json server.

Search Functionality: Filter through products in real-time as you type.

CRUD Operations:

Create: Add new coffee blends via a controlled form.

Read: View current stock and details.

Update: Edit product prices dynamically using PATCH requests.

Responsive Design: A mobile-first layout that adjusts from desktop grids to mobile stacks.

# Tools Used
Frontend: React (Vite)

Routing: React Router DOM

State Management: useState, useEffect, and Props.

Backend: JSON Server (Simulated REST API)

Testing: Vitest & React Testing Library

Styling: CSS3 (Flexbox & Grid)

# Setup & Installation
1. Clone the repository
Bash
git clone <https://github.com/Fasman25/personal-project-showcase-app>
cd brew-admin

2. Install Dependencies
Bash
npm install

3. Start the Backend Server
This project uses json-server to simulate a database. In a separate terminal tab, run:

Bash
npx json-server --watch db.json --port 3001

4. Start the Frontend (Vite)
In your main terminal, run:

Bash
npm run dev
Open http://localhost:5173 (or the port shown in your terminal) to view the app.

# Testing
To run the unit tests for form submissions and routing:

Bash
npm test

# Limitations
Data persistence is limited to the local db.json file.

# Author
Fatuma Asman
