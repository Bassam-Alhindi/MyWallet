<p align="center">
  <img src="./mywallet-banner.svg" alt="MyWallet — AI-Powered Personal Finance" width="100%">
</p>
MyWallet is a modern, mobile-first personal expense tracking and budgeting web application built on the Laravel + Svelte + Inertia.js stack. It includes an embedded AI Assistant that provides proactive spending insights, transaction categorization, and interactive reporting — with full Arabic/English localization and native Saudi Riyal (ر.س) support.

✨ Key Highlights
🤖 Embedded AI Assistant — a smart conversational feature to log expenses from natural chat, detect spending anomalies, and receive tailored financial insights.
📊 Interactive Financial Dashboard — dynamic charts (pie, bar, trends) with custom date filters to monitor net balance and savings rate.
🎨 Spotify-Inspired Dark UI — a premium, mobile-first layout engineered for fast performance and modern aesthetics.
🇸🇦 Dual Localization & SAR Support — seamless Arabic/English switching with full RTL support and native Saudi Riyal currency formatting.
⚡ Modern Type-Safe Full Stack — lightning-fast SPA rendering powered by Inertia v3, Svelte, and TypeScript.
🛠️ Architecture & Tech Stack
Layer	Technology
Backend Core	PHP 8.5 + Laravel Framework
Frontend Engine	Svelte + Inertia.js v3
Styling	Tailwind CSS (Dark-Mode First)
Type Safety	TypeScript Integration
Build & Dev Tools	Vite, Docker, Laravel Boost, PHPUnit
🚀 Quick Start
bash
# 1. Clone the repository
git clone https://github.com/Bassam-Alh/MyWallet.git
cd MyWallet

# 2. Install PHP & Node dependencies
composer install
npm install

# 3. Environment setup & application key
cp .env.example .env
php artisan key:generate

# 4. Database migration & seeding
php artisan migrate --seed

# 5. Start development server
composer run dev
📋 Requirements
PHP 8.5+
Composer
Node.js & npm
Docker (optional, for containerized development)
🤝 Contributing

Contributions, issues, and feature requests are welcome. Feel free to open a pull request or an issue.
