<div align="center">
  <h1>Garden Module</h1>
  <p>A self-contained Next.js application for browsing, tracking, and managing your virtual garden 🌱</p>
  <p>
    <a href="https://github.com/SuYirouCrystal/Gardening-App/blob/main/garden/LICENSE"><img src="https://img.shields.io/badge/license-MIT-green" alt="License: MIT"></a>
    <a href="https://github.com/SuYirouCrystal/Gardening-App/actions"><img src="https://img.shields.io/github/actions/workflow/status/SuYirouCrystal/Gardening-App/ci.yml?branch=main" alt="Build Status"></a>
  </p>
</div>

---

>This README follows established best practices—providing only the necessary information to get up and running quickly, while pointing to deeper documentation where needed.

## Table of Contents  
- [Overview](#overview)  
- [Features](#features)  
- [Prerequisites](#prerequisites)  
- [Installation & Setup](#installation--setup)  
- [Directory Structure](#directory-structure)  
- [Configuration](#configuration)  
- [Usage](#usage)  
- [Contributing](#contributing)  
- [License](#license)  

## Overview  
The **garden** module is a Next.js–based sub-application within the Gardening-App monorepo, built with the App Router for file-based routing and server components to deliver SEO-friendly, high-performance pages&#8203;:contentReference[oaicite:1]{index=1}. It enables users to maintain a plant catalog, schedule watering, and visualize growth analytics via React components and Tailwind CSS&#8203;:contentReference[oaicite:2]{index=2}.

## Features  
- **Plant Catalog Management**  
  – Create, edit, and delete plant profiles (species, planting date, care notes)&#8203;:contentReference[oaicite:3]{index=3}.  
- **Watering Scheduler**  
  – Log watering events and get plant-specific schedule recommendations&#8203;:contentReference[oaicite:4]{index=4}.  
- **Growth Analytics Dashboard**  
  – Interactive charts showing historical growth metrics (client-side components with recharts)&#8203;:contentReference[oaicite:5]{index=5}.  
- **Responsive Design**  
  – Fully responsive layouts powered by Tailwind CSS breakpoints and utility classes&#8203;:contentReference[oaicite:6]{index=6}.

## Prerequisites  
- **Node.js** ≥18 (LTS)  
- **npm** ≥8 or **Yarn** ≥1.22  
- **Git** for cloning and version control&#8203;:contentReference[oaicite:7]{index=7}.  

> Long-form documentation (e.g., design decisions, API specs) belongs in a project wiki rather than this README&#8203;:contentReference[oaicite:8]{index=8}.

## Installation & Setup  
1. **Clone the repository**  
   ```bash
   git clone https://github.com/SuYirouCrystal/Gardening-App.git
   ```

2. **Navigate to the garden module**
   ```bash
   cd Gardening-App/garden
   ```

3. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

4. **Run in development mode**
   ```bash
   npm run dev
   # or
   yarn dev
   ```

5. **Open your browser**
   Visit http://localhost:3000/garden to see the app live.

## Directory Structure
```plaintext
garden/
├── public/              # Static assets (images, icons)
├── src/                 # Source code
│   ├── components/      # Reusable React components
│   ├── pages/           # File-based routes (App Router)
│   ├── styles/          # Tailwind CSS config & global styles
│   └── utils/           # Helpers & API clients
├── package.json         # Scripts & dependencies
└── README.md            # Project overview & instructions
```

## Configuration
* Tailwind Theme: Customize in tailwind.config.js (colors, breakpoints)​ Medium.
* API Base URL: Update in src/utils/api.js to point at your backend.
* Custom Routes: Add or remove files under src/pages/ to modify available routes​ GitHub Docs.

## Usage
* Water a Plant: Click the “Water” button on any plant card to log an event.
* View Analytics: Navigate to /dashboard for growth charts.
* Add New Plant: Use the “+ Add Plant” form at the top of the catalog page.

## Contributing
We welcome bug reports and pull requests! Please follow these steps:
1. **Fork** the repo and **create a branch** (git checkout -b feature/my-feature).
2. **Implement** your changes, adhering to the existing code style.
3. **Run linting & tests:**
   ```bash
   npm run lint
   npm test
   ```
4. **Submit** a pull request describing your changes and linking any related issues.

## License
Distributed under the MIT License. See LICENSE for more details​.
```makefile
::contentReference[oaicite:14]{index=14}
```
