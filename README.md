
# StackIt - AI-Powered Developer Q&A Platform

## 🚀 Overview

StackIt is a modern, full-stack question and answer platform designed specifically for developers. Built with cutting-edge technologies, it combines the power of AI assistance with community-driven knowledge sharing to create the ultimate developer collaboration experience.

### ✨ Key Features

- 🤖 **AI-Powered Assistance** - Get intelligent code help with Gemini AI
- 👥 **Community Q&A** - Ask questions and help fellow developers
- 🔐 **Secure Authentication** - Safe and secure user accounts
- 📝 **Rich Text Editor** - Write and format your questions beautifully
- 🏷️ **Smart Tagging** - Organize questions by technology
- 🔔 **Real-time Notifications** - Never miss important updates
- 🎨 **Modern UI** - Clean, responsive design with dark/light mode

## 🛠️ Built With

- **Frontend**: React, TypeScript, Tailwind CSS
- **Backend**: Node.js, Express, PostgreSQL
- **AI**: Google Gemini AI
- **Database**: Drizzle ORM with PostgreSQL

## � Quick Start

### What You Need

- Node.js 18 or higher
- PostgreSQL database
- Google AI API key

### Setup

1. **Get the code**
   ```bash
   git clone <repository-url>
   cd StackIt
   npm install
   ```

2. **Set up your environment**
   
   Create a `.env` file:
   ```env
   DATABASE_URL=your_postgresql_connection_string
   GEMINI_API_KEY=your_gemini_api_key
   SESSION_SECRET=your_random_secret_key
   ```

3. **Initialize database**
   ```bash
   npm run db:push
   ```

4. **Start the app**
   ```bash
   npm run dev
   ```

Visit `http://localhost:5173` to use the app!

## 🤝 Contributing

Want to help make StackIt better? We'd love your contributions!

1. Fork the repository
2. Create a new branch for your feature
3. Make your changes
4. Submit a pull request

Please follow the existing code style and add tests for new features.

## 🙏 Thanks
