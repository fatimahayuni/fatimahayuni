# Hi there! I am Ayuni. 👋

I am a developer focused on software engineering, system architecture, and building minimalist digital tools. 

---

# 👗  Featured Project: Capsulify

**Capsulify** is a web-based digital wardrobe application built with **Next.js** and deployed on **Vercel**. It targets the minimalist fashion community by solving the mathematical problem of combinatorial explosion—helping users visualize, filter, and optimize thousands of outfit permutations from a downsized wardrobe.

## Tech Stack & Architecture

Capsulify is built as a highly performant, type-safe fullstack web application using the following core technologies:

### 🚀 Core Framework & Runtime
* **[Next.js (App Router)](https://nextjs.org/)** - Fullstack React framework handling server-side rendering (SSR), dynamic page routing, and serverless API endpoints.
* **[TypeScript](https://www.typescriptlang.org/)** - Strict type-checking layer built on top of JavaScript to enforce compile-time error catching and code stability.

### 🎨 Frontend & User Interface
* **[React](https://react.dev/)** - Component-driven UI architecture utilizing state hooks and optimized side-effect lifecycles.
* **[Tailwind CSS](https://tailwindcss.com/)** - Utility-first styling framework optimized for responsive UI layouts and rapid design iteration.
* **[PostCSS](https://postcss.org/)** - Pre-processor handling automation, styling optimizations, and asset compilation for production builds.

### 🔐 Auth & Cloud Infrastructure (BaaS)
* **[Clerk](https://clerk.com/)** - Comprehensive authentication provider handling secure user sessions, JWT verification, and account management.
* **[Supabase](https://supabase.com/)** - Backend-as-a-Service architecture providing:
  * **PostgreSQL:** Relational database storing asset properties, profile information, and outfit combinations.
  * **Supabase Storage:** Asset buckets optimized for serving uploaded clothing and outfit image layers.

### 🧪 Quality Assurance & Testing
* **[Playwright](https://playwright.dev/)** - End-to-End (E2E) automation engine used to run browser-level user flow simulations locally.
* **[Vitest](https://vitest.dev/)** - High-speed unit and integration testing engine utilized for verifying state pipelines and core data utilities.
* **[ESLint](https://eslint.org/)** - Static code linter enforcing consistent anti-pattern detection and clean syntax guidelines.

### 📈 Deployment & Monitoring
* **[Vercel](https://vercel.com/)** - Cloud infrastructure platform optimized for hosting edge-rendered Next.js deployments.
* **[Sentry](https://sentry.io/)** - Real-time Application Performance Monitoring (APM) tracking exception logging and production runtime anomalies.

  ----

### 🛠️ Current Technical Focus & Log (June 2026)
I am currently treating the app as a live case study in refactoring and scaling. Here are the core architectural challenges I am actively documenting and tracking:<br><br>

📉 **1. Code Coupling & Regression Management**
  - *Challenge:* Isolating modules to stop the "whack-a-mole" cycle where new feature deployment causes unexpected regressions in existing modules.<br><br>

💥 **2. Permutation Noise Isolation**
  - *Challenge:* 40 clothing items yield ~16,000 distinct combinations. The interface needs an algorithmic filtering layer to suppress invalid or aesthetically clashing variations before rendering.<br><br>


🏷️ **3. Subscription & Resource Allocation Logic**
  - *Challenge:* Mapping cloud resource usage, database hits, and rate limits into a stable, maintainable pricing matrix.<br><br>


📱 **4. Cross-Platform Compilation (iOS)**
  - *Challenge:* Planning the strategic migration from a web-bound Next.js app to a native mobile footprint for the Apple App Store using wrapper frameworks like Capacitor.<br><br>
