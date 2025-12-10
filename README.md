# Personal Developer Portfolio

[![Live Deployment](https://img.shields.io/badge/Live_Deployment-dheerajsaraswat.vercel.app-black?style=flat-square&logo=vercel)](https://dheerajsaraswat.vercel.app/)
[![License](https://img.shields.io/badge/License-MIT-gray?style=flat-square)](LICENSE)


## Overview

This repository contains the source code for my personal portfolio website. The project was engineered to serve as a high-performance, accessible, and centralized hub for my freelance work and case studies.

The architecture focuses on **Core Web Vitals**, utilizing Next.js for server-side rendering and Tailwind CSS for a utility-first styling approach. The content is decoupled from the UI, allowing for seamless updates via structured data files.

## Technical Stack

*   **Framework:** Next.js 14 (App Router)
*   **Language:** TypeScript
*   **Styling:** Tailwind CSS
*   **Animations:** Framer Motion
*   **Icons:** Lucide React
*   **Deployment:** Vercel

## Key Features

*   **Performance:** Optimized for 100/100 Google Lighthouse scores across Performance, Accessibility, Best Practices, and SEO.
*   **Responsive Design:** Mobile-first architecture ensuring consistency across all viewports.
*   **Scalable Structure:** Component-based architecture with Atomic Design principles.
*   **Animations:** Advanced micro-interactions and page transitions utilizing Framer Motion's `AnimatePresence`.
*   **Type Safety:** Fully typed codebase using TypeScript to reduce runtime errors.

## Local Development

Follow these steps to run the project locally.

### Prerequisites

*   Node.js (v18+)
*   npm / yarn / pnpm

### Installation

1.  **Clone the repository**
    ```bash
    git clone https://github.com/Dheeraj-18/portfolio.git
    cd portfolio
    ```

2.  **Install dependencies**
    ```bash
    npm install
    ```

3.  **Start the development server**
    ```bash
    npm run dev
    ```

4.  Open [http://localhost:3000](http://localhost:3000) to view the application.

## Project Architecture

```bash
├── app/                  # Next.js App Router (Pages & Layouts)
├── components/           # Reusable UI Components
│   ├── ui/               # Primitive components (Buttons, Cards)
│   └── sections/         # Page sections (Hero, Projects, Contact)
├── public/               # Static assets
├── lib/                  # Utility functions & types
├── data/                 # JSON/TS data files (Projects, Experience)
└── styles/               # Global styles & Tailwind config
