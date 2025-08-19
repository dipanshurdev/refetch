
<div align="center">
  <img src="public/logo-purple.png" width="200" style="max-width: 200px;">
  <br />
  <br />
  
  **Open-source alternative to YC-controller HN, featuring curated tech news, discussions, and community-driven content.**
  
  <br />
  <br />

  [![Next.js](https://img.shields.io/badge/Next.js-15.2.4-black?style=for-the-badge&logo=next.js)](https://nextjs.org/)
  [![Appwrite](https://img.shields.io/badge/Appwrite-18.2.0-FF6B6B?style=for-the-badge&logo=appwrite)](https://appwrite.io/)
  [![TypeScript](https://img.shields.io/badge/TypeScript-5.0-blue?style=for-the-badge&logo=typescript)](https://www.typescriptlang.org/)
  [![Tailwind CSS](https://img.shields.io/badge/Tailwind-3.4.17-38B2AC?style=for-the-badge&logo=tailwind-css)](https://tailwindcss.com/)
</div>

---

**Refetch** was born from a simple yet powerful idea: create a modern, open-source alternative to Hacker News that combines the best of community-driven curation with intelligent AI-powered content discovery. Free from YC-control, open and transparent, doesn't favor anyone.

<div align="center">

## 🔥 Top Posts Today (Tuesday, August 19, 2025)

*Auto-updated with the highest-scoring community content*

</div>

**🥇 [LLMs and Coding Agents: A Security Nightmare](https://refetch.io/threads/68a3111b000ed5519a67)**
📊 Votes: **2** | ⏰ 20 hours ago | 🔗 [Original](https://garymarcus.substack.com/p/llms-coding-agents-security-nightmare)

**🥈 [Mastering Data Ingestion: How to Handle 1B Rows/s in ClickHouse](https://refetch.io/threads/68a34cff003b5bd6f07f)**
📊 Votes: **1** | ⏰ 16 hours ago | 🔗 [Original](https://www.tinybird.co/blog-posts/1b-rows-per-second-clickhouse)

**🥉 [Persistent Risk: XZ Utils Backdoor in Docker Images](https://refetch.io/threads/68a3c7da001d8865de43)**
📊 Votes: **0** | ⏰ 7 hours ago | 🔗 [Original](https://www.binarly.io/blog/persistent-risk-xz-utils-backdoor-still-lurking-in-docker-images)

**⭐ [Comparing Update Performance: ClickHouse vs PostgreSQL](https://refetch.io/threads/68a21e4b001f5170c779)**
📊 Votes: **-1** | ⏰ 1 day ago | 🔗 [Original](https://clickhouse.com/blog/update-performance-clickhouse-vs-postgresql)

**⭐ [AI Speed: A Crisis in the Making?](https://refetch.io/threads/68a3770800196b1b165a)**
📊 Votes: **2** | ⏰ 13 hours ago | 🔗 [Original](https://venturebeat.com/ai/the-looming-crisis-of-ai-speed-without-guardrails/)

---

*Last updated: 2025-08-19T08:02:00.828Z*



### What We're Building

- **🤖 AI-Powered Discovery**: Our intelligent scout functions automatically discover high-quality tech content from leading sources so you can be lazy and enjoy
- **🎯 Quality Curation**: Advanced algorithms analyze and rank content based on relevance, quality, and community value
- **🌍 Global Reach**: Multilingual support with AI-powered translations in 12+ languages
- **🔒 Privacy-First**: Built on Appwrite's secure, self-hostable backend infrastructure
- **📱 Modern UX**: Modern, responsive interface built with Next.js 15 and Tailwind CSS, the opposite of HN
- **🚀 Open Source**: 100% open source, community-driven

### Why Refetch?

While Hacker News has been the go-to platform for tech discussions for years, we believe there's room for innovation. Refetch brings:

- **Better Content Discovery**: AI algorithms that surface the most relevant tech news
- **Enhanced User Experience**: Modern, mobile-first design that works everywhere
- **Community Empowerment**: Open source codebase that anyone can contribute to
- **Transparent Algorithms**: Clear, documented ranking systems you can understand and improve

---

## 🏗️ Architecture Overview

Refetch is built with a modern, scalable architecture that prioritizes performance, maintainability, and developer experience.

### Frontend Stack

- **Next.js 15**: React framework with App Router, Server Components, and streaming
- **TypeScript**: Full type safety across the entire codebase
- **Tailwind CSS**: Utility-first CSS framework with custom design system

### Backend Infrastructure

- **Appwrite**: Complete backend-as-a-service platform
  - **Databases**: Collections for posts, comments, users, and votes
  - **Authentication**: User management with JWT tokens
  - **Functions**: Serverless functions for content processing
  - **Sites**: Next.js hosting with built-in CDN and DDoS protection

### AI-Powered Features

- **Content Scout**: Automatically discovers tech articles from 20+ sources
- **Content Enhancement**: AI analysis for quality scoring, categorization, and optimization
- **Smart Ranking**: Multi-factor algorithm considering time, quality, and community engagement
- **Multilingual Support**: AI-powered translations and language detection

---

## 📁 Project Structure

```
refetch/
├── app/                    # Next.js App Router pages
│   ├── (main)/            # Main application routes
│   ├── api/               # API endpoints
│   ├── auth/              # Authentication flows
│   └── globals.css        # Global styles
├── components/             # Reusable React components
│   ├── ui/                # Base UI components (Radix + Tailwind)
│   └── [feature]/         # Feature-specific components
├── contexts/               # React contexts (auth, theme)
├── functions/              # Appwrite serverless functions
│   ├── scout/             # Content discovery automation
│   ├── enhancement/       # AI content analysis
│   └── algorithm/         # Ranking algorithm
├── hooks/                  # Custom React hooks
├── lib/                    # Utility libraries and configurations
├── extensions/             # Browser extensions
└── styles/                 # Additional styling
```

### Key Directories Explained

- **`app/`**: Next.js 15 App Router with server and client components
- **`components/ui/`**: Reusable UI components built on Radix UI primitives
- **`functions/`**: Appwrite serverless functions for backend processing
- **`lib/`**: Core utilities, Appwrite client, and type definitions
- **`extensions/`**: Chrome extension for seamless Refetch integration

---

## 🚀 Getting Started

### Prerequisites

- Node.js 18+ 
- pnpm (recommended) or npm
- Appwrite instance (self-hosted or cloud)

### Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/refetch-io/refetch.git
   cd refetch
   ```

2. **Install dependencies**
   ```bash
   pnpm install
   ```

3. **Set up environment variables**
   ```bash
   cp env.example .env.local
   # Edit .env.local with your Appwrite credentials
   ```

4. **Run the development server**
   ```bash
   pnpm dev
   ```

5. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

### Environment Configuration

Create a `.env.local` file with your Appwrite configuration:

```env
# Appwrite Configuration
NEXT_PUBLIC_APPWRITE_ENDPOINT=your_appwrite_endpoint
NEXT_PUBLIC_APPWRITE_PROJECT_ID=your_project_id
NEXT_PUBLIC_APPWRITE_DATABASE_ID=your_database_id

# OpenAI API Key (for AI features)
OPENAI_API_KEY=your_openai_api_key

# Appwrite API Keys
APPWRITE_API_KEY=your_api_key
```

---

## 🤝 Contributing

**Refetch was initially 100% vibe-coded, but we're excited to welcome contributions from humans too!** 

We believe in the power of community-driven development and welcome all types of contributions:

### How to Contribute

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/amazing-feature
   ```
3. **Make your changes**
4. **Test thoroughly**
5. **Submit a pull request**

---

## 🔧 Appwrite Functions

Refetch uses several Appwrite serverless functions for automated content processing:

### Scout Function
Automatically discovers high-quality tech content from 20+ sources including TechCrunch, The Verge, Ars Technica, and more.

### Enhancement Function
AI-powered content analysis that generates metadata, quality scores, and multilingual translations.

### Algorithm Function
Sophisticated ranking algorithm that considers time decay, quality metrics, and community engagement.

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<div align="center">
  <p><strong>Made with ❤️ for the Refetch community</strong></p>
</div>
