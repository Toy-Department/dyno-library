# DynoLibrary

DynoLibrary is a comprehensive platform designed for automotive enthusiasts to store, share, and analyze vehicle dynamometer (dyno) results. It serves as a centralized database where users can explore performance metrics across different vehicle builds, modifications, and tuning setups.

**Check it out at: [www.dynolibrary.com](https://www.dynolibrary.com)**

## 🚀 About the Project

DynoLibrary allows users to:
- **Explore Performance Data**: Search and filter vehicles by year, make, model, engine, and transmission to find real-world performance numbers.
- **Visualize Power Curves**: View interactive horsepower and torque graphs to understand power delivery characteristics.
- **Manage Builds**: Create profiles to track vehicle modifications and upload dyno sheets.
- **Analyze Results**: Leverage automated tools to extract data from dyno sheets.

## 🛠️ Tech Stack

This project is built with a modern, high-performance stack:

### Core
- **[Next.js 15](https://nextjs.org/)**: The React framework for the web, utilizing the App Router for server-side rendering and static generation.
- **[React 19](https://react.dev/)**: The latest version of React for building interactive user interfaces.
- **[TypeScript](https://www.typescriptlang.org/)**: For type-safe code and better developer experience.

### Styling & UI
- **[Tailwind CSS 4](https://tailwindcss.com/)**: A utility-first CSS framework for rapid UI development.
- **[Lucide React](https://lucide.dev/)**: Beautiful, consistent icons.

### Backend & Services
- **[Supabase](https://supabase.com/)**: An open-source Firebase alternative providing:
    - **Database**: PostgreSQL for structured data storage.
    - **Authentication**: Secure user sign-up and login flows.
    - **Storage**: Managing vehicle images and dyno sheets.
- **[Vercel](https://vercel.com/)**: Hosting and deployment platform optimized for Next.js.
- **[Resend](https://resend.com/)**: For reliable email delivery (transactional emails, notifications).
- **[Google Cloud Vision API](https://cloud.google.com/vision)**: Used for optical character recognition (OCR) to extract data from uploaded dyno sheets automatically.

## ⚠️ Note on Deployment

**This repository contains the source code for DynoLibrary. The code is not currently published or deployed from this public repository due to security considerations and ongoing development.**

We are sharing this README to showcase the architecture and technologies used in building this application.
