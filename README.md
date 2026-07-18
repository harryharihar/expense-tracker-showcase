# Expense Intelligence — Public Showcase

This is a public summary repo for a private project. It shares the tech stack and high-level highlights only; no source code is included here.

## Live App / Screenshots

Check out the live app landing page and screenshots here: https://www.spendkar.com/

## About

AI-powered expense tracking app with multi-account support, spending predictions, and financial insights.

## Tech Stack

Mobile: React Native (TypeScript) with Redux Toolkit. Backend: NestJS, TypeORM, and PostgreSQL, with Redis for caching and Socket.io for real-time updates. AI/ML service: Python and FastAPI, using scikit-learn and numpy for predictive analytics and Pytesseract for OCR. Infrastructure: Docker Compose and Nginx, with CI/CD automated through a container registry.

## Key Highlights

The project features a unified transaction categorization engine that combines rules-based matching with AI fallback for PDF, SMS, and manual imports. It includes bank statement OCR parsing supporting over twenty Indian banks using a mix of regex and ML-assisted extraction. Real-time balance updates are delivered via WebSockets, backed by Redis-cached account queries and atomic multi-account transfers. The analytics suite covers spending predictions, subscription detection, and category trend analysis, alongside a client-side AI assistant. The infrastructure is production-hardened with health checks, security headers, and automated CI/CD deployment.

## Note

The source code for this project is kept in a private repository. This page exists to share the project's architecture and stack publicly without exposing the codebase.
