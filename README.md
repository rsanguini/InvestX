<h1 align="center"> InvestX </h1>

### AI-Powered Investment Platform for Modern Investors

<p align="center">
Real-time market data • AI-powered financial analysis • Portfolio management • Trading simulation • Built with Vanilla JavaScript
</p>

<p align="center">

<a href="https://investx-black.vercel.app">
<img src="https://img.shields.io/badge/Live_Demo-Visit_Website-red?style=for-the-badge">
</a>

<a href="../../issues">
<img src="https://img.shields.io/badge/Report-Bug-black?style=for-the-badge">
</a>

<a href="../../issues">
<img src="https://img.shields.io/badge/Request-Feature-red?style=for-the-badge">
</a>

</p>

<p align="center">

<img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white">

<img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white">

<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black">

<img src="https://img.shields.io/badge/Groq-AI-black?style=flat-square">

<img src="https://img.shields.io/badge/Yahoo-Finance-purple?style=flat-square">

<img src="https://img.shields.io/badge/Vercel-Deploy-black?style=flat-square&logo=vercel">

<img src="https://img.shields.io/badge/License-MIT-red?style=flat-square">

</p>

</div>

---

# Preview

## Landing Page

<p align="center">
<img width="1856" height="946" alt="Landing page - InvestX" src="https://github.com/user-attachments/assets/8c1577f6-e6ca-44bc-8468-09aa9726c8ee" />

</p>

---

## Dashboard

<p align="center">
<img width="1867" height="951" alt="dashboard page" src="https://github.com/user-attachments/assets/2d704230-c1e2-484b-8c34-474d598e916f" />

</p>

---

## Omega AI Assistant

<p align="center">
<img width="415" height="678" alt="OMega IA - InvestX" src="https://github.com/user-attachments/assets/3b0d2426-0efa-4af4-a932-c9ca2b6931dd" />
</p>

---

# About

**InvestX** is a modern investment platform currently under active development, designed to combine real-time financial data with artificial intelligence to help investors make better decisions.

The long-term vision is to transform InvestX into a complete **Full-Stack FinTech ecosystem**, providing portfolio management, technical analysis, market intelligence, investment simulations, and an AI-powered financial assistant capable of understanding both market conditions and user profiles.

Unlike many educational projects, InvestX was intentionally built without frontend frameworks. The application demonstrates how a scalable and modular architecture can be achieved using only **HTML, CSS and Vanilla JavaScript**, while integrating external APIs and serverless functions.

The project is continuously evolving with new features, backend services and infrastructure improvements.

---

# Why InvestX?

The objective of this project goes beyond creating another investment dashboard.

InvestX was built to demonstrate practical software engineering skills, including:

- Clean architecture
- Modular JavaScript
- API integration
- Financial data processing
- Responsive UI/UX
- AI integration
- Authentication
- Trading simulations
- Deploy automation
- Scalability

The project also serves as the foundation for a future commercial platform.

---

# Key Features

### Real-Time Market Data

- Live stock prices
- Cryptocurrency quotes
- Market indexes
- Automatic refresh
- Yahoo Finance integration

---

### Omega AI

A conversational AI specialized in financial analysis capable of assisting users with:

- Brazilian stocks
- ETFs
- REITs (FIIs)
- Cryptocurrencies
- Fixed income
- Technical analysis
- Fundamental analysis
- Portfolio diversification
- Macroeconomic scenarios

Powered by **Groq AI** with real-time market context.

---

### Portfolio Management

Manage your investments through an interactive dashboard.

Features include:

- Asset registration
- Average price calculation
- Portfolio allocation
- Profit & loss analysis
- Performance tracking
- AI investment score

---

### Trading Simulator

Practice investment strategies without risking real money.

Includes:

- Market Orders
- Limit Orders
- Stop Orders
- Stop Gain
- DCA Simulator
- Compound Interest Calculator
- AI-generated investment commentary

---

### Intelligent Alerts

Create custom alerts for your favorite assets.

Receive notifications whenever a target price is reached.

---

### Authentication

- User registration
- Login system
- Demo account
- Local persistence
- Profile customization

---

### Responsive Interface

Designed with a professional trading-terminal aesthetic featuring:

- Dark mode interface
- Responsive layout
- Animated components
- Live dashboard
- Modern typography

---

# Tech Stack

| Category | Technologies |
|-----------|--------------|
| Frontend | HTML5 |
| Styling | CSS3 |
| Programming Language | Vanilla JavaScript |
| Charts | Canvas API |
| Artificial Intelligence | Groq API |
| Market Data | Yahoo Finance API |
| Storage | LocalStorage |
| Authentication | Custom Authentication |
| Deployment | Vercel |
| Version Control | Git & GitHub |

---

# Project Highlights

✔ Modular Architecture

✔ Vanilla JavaScript

✔ Serverless API

✔ Responsive Design

✔ AI Integration

✔ Real-Time Market Data

✔ Trading Simulator

✔ Portfolio Dashboard

✔ Technical Analysis

✔ Fundamental Analysis

✔ Investment Alerts

✔ Production Ready UI

✔ Full Documentation

✔ Future Full-Stack Architecture

---

> **Designed as a portfolio project today. Built to become a real product tomorrow.**

# Architecture

InvestX follows a modular architecture that separates the application into independent layers, making the project easier to maintain, scale and evolve into a complete Full-Stack platform.

```text
                                User
                                  │
                                  ▼
                         HTML / CSS / JavaScript
                                  │
          ┌───────────────────────┼───────────────────────┐
          │                       │                       │
          ▼                       ▼                       ▼
    Authentication         Dashboard UI           Omega AI Chat
          │                       │                       │
          └───────────────┬───────┴───────────────┬───────┘
                          │                       │
                          ▼                       ▼
                   Market Module          Trading Simulator
                          │
                          ▼
                Yahoo Finance API
                          │
                          ▼
                 Serverless Functions
                          │
                          ▼
                      Groq AI API
```

The architecture was intentionally designed to remain modular and framework-independent while supporting future backend services and database integration.

---

# Project Structure

```text
InvestX
│
├── api/
│   ├── chat.js                 # Serverless AI endpoint
│   └── market.js               # Market API proxy
│
├── CSS/
│   ├── auth.css
│   ├── home.css
│   ├── login.css
│   ├── profile.css
│   ├── register.css
│   └── style.css
│
├── HTML/
│   ├── Home.html
│   ├── index.html
│   ├── login.html
│   └── register.html
│
├── Images/
│   ├── logo.png
│   ├── grafico.webp
│   ├── robo.png
│   ├── camera.png
│   └── ...
│
├── JS/
│   ├── app.js
│   ├── auth.js
│   ├── chart.js
│   ├── chat.js
│   ├── config.js
│   ├── home.js
│   ├── index.js
│   ├── login.js
│   ├── market.js
│   ├── perfil.js
│   ├── trading.js
│   └── ui.js
│
├── vercel.json
│
├── LICENSE
│
└── README.md
```

---

# Technology Stack

## Frontend

- HTML5
- CSS3
- Vanilla JavaScript

## APIs

- Yahoo Finance API
- Groq AI API

## Deployment

- Vercel

## Storage

- LocalStorage

## Charts

- Canvas API

---

# Getting Started

Clone the repository:

```bash
git clone https://github.com/rsanguini/InvestX.git
```

Enter the project folder:

```bash
cd InvestX
```

---

## Run Locally

Since the project uses Vanilla JavaScript, no build process is required.

You can use any local web server.

### Option 1 — Live Server (Recommended)

Open the project using the **Live Server** extension in Visual Studio Code.

---

### Option 2 — Python

```bash
python -m http.server 8080
```

or

```bash
python3 -m http.server 8080
```

---

### Option 3 — Node.js

```bash
npx serve .
```

---

Open your browser:

```text
http://localhost:8080/HTML/Home.html
```

---

# Demo Account

You can explore the platform without creating an account.

```text
Email
demo@investx.com

Password
demo123
```

The demo account includes:

- Sample portfolio
- Trading history
- Price alerts
- Dashboard access
- Omega AI integration

---

# Deployment

InvestX is fully compatible with **Vercel**.

Deploy in minutes:

```bash
npm install -g vercel
```

Login:

```bash
vercel login
```

Deploy:

```bash
vercel
```

Production:

```bash
vercel --prod
```

---

# Environment Variables

To enable Omega AI, create the following environment variable:

```env
GROQ_API_KEY=your_api_key
```

Configure it inside the Vercel Dashboard under:

```text
Project Settings

↓

Environment Variables
```

---

# APIs

## Yahoo Finance

Used for:

- Real-time stock prices
- Cryptocurrency prices
- Market indexes
- Price variation
- Portfolio updates

---

## Groq API

Used to power **Omega AI**.

The assistant is capable of understanding:

- Stocks
- ETFs
- FIIs
- Cryptocurrencies
- Fixed income
- Technical analysis
- Fundamental analysis
- Portfolio diversification
- Market news

---

# Omega AI

Omega AI is the intelligent engine behind InvestX.

Instead of acting like a generic chatbot, Omega AI is designed specifically for financial analysis.

Current capabilities include:

- Real-time market context
- Technical indicators
- Fundamental analysis
- Investment explanations
- Economic scenario interpretation
- Personalized responses
- Portfolio insights
- Investment education

Future versions will include:

- Long-term memory
- Portfolio recommendations
- Watchlists
- News analysis
- Voice interaction
- Multi-agent architecture

---

# Performance

The project was designed with performance as a priority.

### Highlights

- No frontend framework
- No unnecessary dependencies
- Lightweight assets
- Fast loading
- Modular architecture
- Responsive interface
- Serverless backend
- Easy deployment

---

# Security

Current security features include:

- Secure API proxy
- Hidden API keys
- Local authentication
- User session management
- Input validation
- Protected serverless endpoints

Future versions will include:

- JWT Authentication
- Database encryption
- OAuth login
- Two-Factor Authentication
- Cloud database

---

# Roadmap

InvestX is under continuous development.

The long-term goal is to evolve the platform into a complete **AI-powered investment ecosystem**.

## Completed

- Responsive Landing Page
- Authentication System
- Portfolio Dashboard
- Trading Simulator
- Real-Time Market Data
- Omega AI Integration
- Technical Analysis
- Fundamental Analysis
- Investment Alerts
- Serverless Deployment

---

## In Progress

- Backend Architecture
- User Database
- API Refactoring
- Performance Optimization
- Better State Management
- Improved Mobile Experience

---

## Planned Features

### Authentication

- JWT Authentication
- OAuth Login (Google / GitHub)
- Two-Factor Authentication

### Portfolio

- Persistent Cloud Portfolio
- Portfolio Performance Reports
- Dividend Tracking
- Asset Allocation Analysis

### Trading

- Watchlists
- Advanced Order Types
- Risk Management Tools
- Position Sizing Calculator

### AI

- AI Portfolio Review
- AI Risk Assessment
- Investment Recommendations
- News Summarization
- Voice Assistant
- Long-Term Memory
- Multi-Agent Architecture

### Market

- Official B3 API
- Economic Calendar
- Market News Feed
- ETF Database
- International Markets
- Commodities
- Forex

### Infrastructure

- Node.js Backend
- PostgreSQL Database
- Docker Support
- CI/CD Pipeline
- Automated Testing
- Monitoring
- Logging

---

# Project Vision

InvestX is much more than a dashboard.

The vision is to build an intelligent financial platform capable of assisting investors throughout their entire investment journey.

The platform is being designed with scalability in mind, allowing future integration with cloud databases, authentication providers, AI services, broker APIs, and advanced portfolio analytics.

Every feature added today is planned with the future Full-Stack architecture in mind.

---

# Why Vanilla JavaScript?

Instead of relying on frontend frameworks, InvestX was intentionally developed using **Vanilla JavaScript**.

This decision highlights:

- Strong JavaScript fundamentals
- Modular architecture
- Performance optimization
- Deep understanding of browser APIs
- Clean dependency management

The goal is to demonstrate that scalable applications can be built without unnecessary complexity while keeping the project easy to understand and maintain.

---

# Contributing

Contributions are always welcome.

If you would like to improve InvestX, feel free to:

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature/amazing-feature
```

3. Commit your changes

```bash
git commit -m "feat: add amazing feature"
```

4. Push your branch

```bash
git push origin feature/amazing-feature
```

5. Open a Pull Request

Please make sure your code follows the existing project structure and coding style.

---

# Support

If you found this project useful, consider giving it a ⭐ on GitHub.

It helps the project gain visibility and motivates future development.

---

# License

This project is distributed under the **MIT License**.

See the **LICENSE** file for more information.

---

# Author

<div align="center">

## Rafael Sanguini Colagrossi

Software Developer passionate about Artificial Intelligence, Financial Technology and Full-Stack Development.

Building modern software focused on performance, clean architecture and great user experience.

<br>

<a href="https://github.com/rsanguini">
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white">
</a>

<a href="https://linkedin.com/in/rafaelsanguini">
<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white">
</a>

<a href="mailto:rafaelcolagrossi@gmail.com">
<img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white">
</a>

</div>

---

<div align="center">

## InvestX

### AI-Powered Investing for Everyone.

Building the future of intelligent investing, one commit at a time.

⭐ **If you like this project, don't forget to star the repository!**

</div>
