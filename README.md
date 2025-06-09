# NextjsCRM


<p align="center">
  A modern, AI-powered CRM solution built with Next.js 15, TypeScript, and cutting-edge technologies
</p>

<p align="center">
  <a href="#features"><strong>Features</strong></a> ·
  <a href="#tech-stack"><strong>Tech Stack</strong></a> ·
  <a href="#installation"><strong>Installation</strong></a> ·
  <a href="#roadmap"><strong>Roadmap</strong></a> ·
</p>

---

## About

NextjsCRM is a comprehensive Customer Relationship Management starter built on top of **Next.js 15** using **TypeScript**. It combines the beautiful **shadcn/ui** component library with **Prisma ORM** and **PostgreSQL** for robust data management. 

Built upon the foundation of the awesome NextCRM project by Pavel Dovhomilja, NextjsCRM features an advanced workflow engine inspired by Nisarg Bhatt's Workflow-Engine project, enhanced with AI capabilities for modern business automation.

## ✨ Key Features

### 🚀 Core CRM Functionality
- **Contact Management** - Comprehensive customer data management
- **Project Tracking** - Advanced project management with workflow automation
- **Task Management** - Organized task tracking and assignment
- **Reports & Analytics** - Beautiful charts and insights using Tremor

### 🤖 AI-Powered Features
- **Automated Email Notifications** - AI-generated content using OpenAI API
- **Invoice Data Parsing** - Intelligent document processing with Rossum AI
- **Daily Summaries** - Automated project and task summaries

### 📧 Communication Tools
- **Email Integration** - Built-in email client with SMTP/IMAP support
- **Email Templates** - Beautiful, responsive templates with React Email
- **Email Campaigns** - Marketing automation (planned)

### 🌍 International Support
- **Multi-language Support** - i18n localization with next-intl
- **Timezone Management** - Global business support

## 🛠 Tech Stack

### Frameworks & Core
- **[Next.js 15](https://nextjs.org/)** - React framework with App Router
- **[TypeScript](https://www.typescriptlang.org/)** - Type-safe development
- **[Auth.js](https://authjs.dev/)** - Authentication with multiple providers
- **[Prisma ORM](https://www.prisma.io/)** - Type-safe database operations

### Database & Storage
- **[PostgreSQL](https://postgresql.org/)** - Primary database
- **[Tembo](https://tembo.io/)** - Managed PostgreSQL hosting
- **[UploadThing](https://uploadthing.com/)** - File storage and management

### UI & Styling
- **[Tailwind CSS](https://tailwindcss.com/)** - Utility-first CSS framework
- **[shadcn/ui](https://ui.shadcn.com/)** - Beautiful, accessible components
- **[Tremor](https://www.tremor.so/)** - Data visualization and charts

### Data Management
- **[TanStack Query](https://tanstack.com/query)** - Server state management
- **[SWR](https://swr.vercel.app/)** - Data fetching hooks
- **[Axios](https://axios-http.com/)** - HTTP client
- **Server Actions** - Native Next.js data mutations

### AI & Automation
- **[OpenAI API](https://openai.com/)** - AI-powered features
- **[Rossum](https://rossum.ai/)** - Document AI processing

### Email & Communication
- **[Resend](https://resend.com/)** - Email delivery service
- **[React Email](https://react.email/)** - Email template framework

### Deployment
- **[Vercel](https://vercel.com/)** - Seamless deployment and hosting


 

## 🚀 Quick Start

### Prerequisites
- Node.js 18+ 
- PostgreSQL database
- npm or yarn package manager

### Local Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/phsphd/nextjscrm_supabase.git
   cd NextjsCRM
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   ```bash
   cp .env.example .env
   cp .env.local.example .env.local
   ```
   
   Configure your environment variables:
   - **`.env`** - PostgreSQL connection string for Prisma
   - **`.env.local`** - NextAuth, UploadThing, Rossum, OpenAI, and email configurations

4. **Initialize the database**
   ```bash
   npx prisma generate
   npx prisma db push
   npx prisma db seed
   ```

5. **Start the development server**
   ```bash
   npm run dev
   ```

6. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

 

## 🗺 Roadmap

### 🔄 In Progress
- [ ] Enhanced AI features - Daily task and project summaries
- [ ] Complete i18n localization support
- [ ] Advanced marketing automation tools

### 📋 Planned
- [ ] Email campaign management (MailChimp & Listmonk integration)
- [ ] Comprehensive testing suite (Jest + Cypress)
- [ ] Turborepo monorepo structure
- [ ] Built-in email client
- [ ] Enhanced workflow automation

### ✅ Completed
- [x] Next.js 15 upgrade
- [x] Complete TypeScript migration
- [x] Docker containerization
- [x] Core CRM functionality
- [x] AI-powered features foundation

 

## 🤝 Contributing

We welcome contributions! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch** (`git checkout -b feature/amazing-feature`)
3. **Commit your changes** (`git commit -m 'Add amazing feature'`)
4. **Push to the branch** (`git push origin feature/amazing-feature`)
5. **Open a Pull Request**

### Areas where we need help:
- 🧪 Testing (Jest + Cypress)
- 🌍 Localization and translations
- 📱 Mobile responsiveness improvements
- 🎨 UI/UX enhancements

## 🐛 Issues & Support

- **Bug Reports**: [Open an issue](https://github.com/phsphd/nextjscrm_supabase/issues)
- **Feature Requests**: [Request a feature](https://github.com/phsphd/nextjscrm_supabase/issues/new)
 

## 📊 Repository Activity

![Repository Activity](https://repobeats.axiom.co/api/embed/2e232d8085eb660d127f4d8885e560dd08450630.svg)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Pavel Dovhomilja** - Original NextCRM project foundation
- **Nisarg Bhatt** - Workflow engine inspiration and TypeScript improvements
- **shadcn** - Beautiful UI component library
- **Vercel Team** - Next.js framework and deployment platform

---

<div align="center">
  <p>Built with ❤️ by Excellgen team</p>
  <p>
    <a href="https://crm.excellgen.com">Website</a> ·
 
  </p>
</div>
