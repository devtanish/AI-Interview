# AI Interview

> AI-powered interview tool that analyzes answers and provides instant, personalized feedback for effective preparation.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-View%20App-blue)](https://lovable.dev/projects/22c8fd13-a4b8-4d3a-92e5-7b9b73099412)
[![GitHub](https://img.shields.io/github/license/devtanish/AI-Interview)](LICENSE)
[![React](https://img.shields.io/badge/React-18+-61DAFB?logo=react)](https://reactjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5+-3178C6?logo=typescript)](https://www.typescriptlang.org/)

## 📸 Screenshots

![Project Screenshot](https://drive.google.com/uc?export=view&id=1ErPHm6_ewz-oC4l3W3h7H28ZisWZIRQp)

![Project Screenshot](https://drive.google.com/uc?export=view&id=1VEbMBePUIDSS_UDF1VaRcVWKKeEo4ORl)

![Project Screenshot](https://drive.google.com/uc?export=view&id=1rGly7cNmB-VRfApIMre3knwyCucrzXa-)

## 🎯 Overview

AI Interview is a comprehensive interview preparation platform that leverages artificial intelligence to simulate real interview scenarios. The application provides instant feedback on your responses, helping you identify areas for improvement and build confidence for your actual interviews.

## ✨ Features

- 🤖 **AI-Powered Questions** - Dynamic question generation based on role and experience level
- 📊 **Real-time Analysis** - Instant feedback on communication skills and answer quality  
- 🎙️ **Voice Recognition** - Speech-to-text for natural conversation flow
- 📈 **Performance Tracking** - Detailed analytics and progress monitoring
- 🔐 **Secure Authentication** - User management with Clerk integration
- 💬 **Real-time Communication** - WebSocket integration for seamless interactions
- 🎨 **Modern UI/UX** - Clean, responsive interface built with Tailwind CSS
- 📱 **Mobile Responsive** - Optimized for all devices

## 🛠️ Tech Stack

| Category | Technology | Purpose |
|----------|------------|---------|
| **Frontend** | React 18+ | User interface framework |
| **Language** | TypeScript | Type-safe development |
| **Build Tool** | Vite | Fast development and bundling |
| **Styling** | Tailwind CSS | Utility-first styling |
| **State Management** | Redux Toolkit | Predictable state management |
| **Authentication** | Clerk | User authentication & management |
| **Real-time** | WebSocket | Live communication |
| **Validation** | Zod | Runtime type validation |
| **UI Components** | shadcn/ui | Reusable component library |

## 🚀 Quick Start

### Prerequisites

- Node.js 18+ and npm
- Git

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/devtanish/AI-Interview.git
   cd AI-Interview
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   ```bash
   cp .env.example .env.local
   ```
   
   Update `.env.local` with your configuration:
   ```env
   VITE_CLERK_PUBLISHABLE_KEY=your_clerk_key_here
   VITE_API_BASE_URL=your_api_url_here
   VITE_WEBSOCKET_URL=your_websocket_url_here
   ```

4. **Start the development server**
   ```bash
   npm run dev
   ```

5. **Open your browser**
   Navigate to `http://localhost:5173`

## 📁 Project Structure

```
AI-Interview/
├── public/                 # Static assets
├── src/
│   ├── components/        # Reusable UI components
│   │   ├── ui/           # shadcn/ui components
│   │   ├── interview/    # Interview-specific components
│   │   └── common/       # Shared components
│   ├── pages/            # Application pages/routes
│   ├── hooks/            # Custom React hooks
│   ├── store/            # Redux store configuration
│   │   ├── slices/      # Redux slices
│   │   └── api/         # API slice definitions
│   ├── lib/             # Utility libraries
│   ├── types/           # TypeScript type definitions
│   ├── schemas/         # Zod validation schemas
│   └── styles/          # Global styles
├── package.json
├── tsconfig.json
├── tailwind.config.js
├── vite.config.ts
└── README.md
```

## 🔧 Available Scripts

```bash
# Development
npm run dev          # Start development server
npm run build        # Build for production  
npm run preview      # Preview production build locally

# Code Quality
npm run lint         # Run ESLint
npm run lint:fix     # Fix ESLint issues
npm run type-check   # Run TypeScript compiler

# Testing
npm run test         # Run tests
npm run test:ui      # Run tests with UI
```
### Custom Domain Setup
To use a custom domain with Lovable:
1. Go to **Project → Settings → Domains**
2. Click **Connect Domain**
3. Follow the DNS configuration steps

## 🎮 Usage

1. **Sign Up/Login** - Create an account or sign in with existing credentials
2. **Choose Interview Type** - Select from technical, behavioral, or custom interviews
3. **Set Parameters** - Configure difficulty level, duration, and focus areas
4. **Start Interview** - Begin your AI-powered interview session
5. **Review Feedback** - Analyze your performance and improvement suggestions
6. **Track Progress** - Monitor your improvement over time

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guidelines](CONTRIBUTING.md) for details.

### Development Workflow

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/amazing-feature`
3. Make your changes and add tests
4. Commit your changes: `git commit -m 'Add amazing feature'`
5. Push to the branch: `git push origin feature/amazing-feature`
6. Open a Pull Request

### Code Style

- Use TypeScript for all new code
- Follow the existing ESLint configuration
- Write meaningful commit messages
- Add tests for new features

## 🐛 Issues & Support

- 🐛 [Report a bug](https://github.com/devtanish/AI-Interview/issues/new?template=bug_report.md)
- 🚀 [Request a feature](https://github.com/devtanish/AI-Interview/issues/new?template=feature_request.md)
- 💬 [Join discussions](https://github.com/devtanish/AI-Interview/discussions)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Tanish** 
- GitHub: [@devtanish](https://github.com/devtanish)
- LinkedIn: [Connect with me](https://www.linkedin.com/in/tanish-vishwakarma/)

## 🙏 Acknowledgments

- [React](https://reactjs.org/) - The foundation of our UI
- [Clerk](https://clerk.com/) - Authentication made simple  
- [shadcn/ui](https://ui.shadcn.com/) - Beautiful component library
- [Tailwind CSS](https://tailwindcss.com/) - Utility-first CSS framework
- [Lovable](https://lovable.dev/) - Rapid development platform

## 📈 Roadmap

- [ ] Multi-language support
- [ ] Video interview simulation
- [ ] Advanced analytics dashboard
- [ ] Integration with job platforms
- [ ] Mobile app development
- [ ] AI interviewer personality customization

---

<div align="center">

**[⭐ Star this repo](https://github.com/devtanish/AI-Interview)** if you found it helpful!

Made with ❤️ by [Tanish](https://github.com/devtanish)

</div>
