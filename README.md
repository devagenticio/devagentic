# DevAgentic - AI Agent Platform

## 🚀 Overview

DevAgentic is a production-grade web application for designing, deploying, and managing intelligent AI agents. Built with modern web technologies and enterprise-grade security, it provides a developer-friendly platform for the next generation of AI-powered solutions.

## 📋 Company Information

- **Company**: DevAgentic LLC
- **Domain**: [devagentic.io](https://devagentic.io)
- **Dashboard**: [dashboard.devagentic.io](https://dashboard.devagentic.io)
- **Contact**: support@devagentic.io

## ✨ Features

### Core Platform Features
- **Visual Agent Builder**: Intuitive drag-and-drop interface for creating AI agents
- **Multi-Model Support**: Integration with GPT-4, Claude, Gemini, and other leading AI models
- **RAG Integration**: Retrieval-Augmented Generation with knowledge base connectivity
- **Plugin Marketplace**: Extensible architecture with pre-built and custom integrations
- **Enterprise Security**: SOC 2 compliance, encryption, and comprehensive audit logs
- **Usage Analytics**: Real-time monitoring and performance optimization tools

### Pricing Plans
- **Free**: Up to 3 agents, 5K API calls/month, basic features
- **Pro**: Unlimited agents, 100K API calls/month, advanced features ($49/month)
- **Enterprise**: Custom pricing with dedicated support and unlimited usage

## 🛠 Technology Stack

- **Frontend**: React 18, TypeScript, Vite
- **Styling**: Tailwind CSS, shadcn/ui components
- **Routing**: React Router DOM
- **State Management**: TanStack Query
- **Form Handling**: React Hook Form with Zod validation
- **UI Components**: Radix UI primitives
- **Animations**: CSS animations and transitions
- **Icons**: Lucide React

## 📁 Project Structure

```
src/
├── components/
│   ├── ui/           # shadcn/ui components
│   └── Layout.tsx    # Main layout component
├── pages/
│   ├── Index.tsx     # Home page
│   ├── Pricing.tsx   # Pricing page
│   ├── Docs.tsx      # Documentation page
│   ├── NotFound.tsx  # 404 page
│   └── legal/        # Legal pages
│       ├── PrivacyPolicy.tsx
│       └── TermsOfService.tsx
├── hooks/
│   └── use-toast.ts  # Toast notifications
├── lib/
│   └── utils.ts      # Utility functions
├── index.css         # Global styles and design system
└── App.tsx           # Main app component
```

## 🎨 Design System

### Brand Colors
- **Primary**: #1F2937 (gray-800)
- **Accent**: #22C55E (green-500)
- **Typography**: Inter font family

### Design Principles
- Clean, modern, premium SaaS aesthetic
- Consistent spacing and typography hierarchy
- Responsive design for all device sizes
- Accessibility-first approach (WCAG AA compliant)
- Smooth animations and micro-interactions

## 🚀 Development

### Prerequisites
- Node.js (18+ recommended)
- npm or yarn package manager

### Getting Started

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd devagentic-frontend
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm run dev
   ```

4. **Build for production**
   ```bash
   npm run build
   ```

5. **Preview production build**
   ```bash
   npm run preview
   ```

### Available Scripts
- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint
- `npm run type-check` - Run TypeScript type checking

## 📱 Pages

### Home Page (/)
- Hero section with value proposition
- Feature showcase (6 key features)
- Customer testimonials carousel
- Company information and leadership
- Contact form and information

### Pricing (/pricing)
- Three-tier pricing structure
- Feature comparison
- Billing information and terms
- CTA buttons linking to dashboard

### Documentation (/docs)
- Quick start guide
- API reference with code examples
- Best practices and tutorials
- SDK examples (JavaScript, Python, REST API)

### Legal Pages
- Privacy Policy (`/legal/privacy-policy`) - GDPR compliant
- Terms of Service (`/legal/terms-of-service`) - UK law governed

## 🔒 Security & Compliance

- **GDPR Compliance**: Full data protection compliance for UK/EU users
- **Privacy-First**: Transparent data handling and user rights
- **Secure Development**: Industry-standard security practices
- **Legal Compliance**: UK company law and data protection regulations

## 🌐 SEO & Performance

- **SEO Optimized**: Proper meta tags, structured data, and semantic HTML
- **Performance**: Optimized bundle size and loading times
- **Accessibility**: WCAG AA compliant for inclusive design
- **Mobile-First**: Responsive design for all devices

## 📦 Deployment

### Production Deployment Options

1. **Vercel** (Recommended)
   ```bash
   npm run build
   # Deploy to Vercel
   ```

2. **Netlify**
   ```bash
   npm run build
   # Deploy dist/ folder to Netlify
   ```

3. **AWS S3 + CloudFront**
   ```bash
   npm run build
   # Upload dist/ to S3 bucket
   ```

4. **Docker**
   ```dockerfile
   FROM nginx:alpine
   COPY dist/ /usr/share/nginx/html/
   EXPOSE 80
   CMD ["nginx", "-g", "daemon off;"]
   ```

### Environment Configuration
- Development: Local development server
- Production: Static build with CDN deployment
- All external links point to `https://dashboard.devagentic.io`

## 📧 Support

For technical support, feature requests, or general inquiries:

- **Email**: support@devagentic.io
- **Response Time**: Within 24 hours
- **Business Hours**: UK business hours (GMT/BST)

## 📄 License

© 2024 DevAgentic LLC. All rights reserved.

This project is proprietary software owned by DevAgentic LLC. Unauthorized copying, modification, or distribution is prohibited.

---

Built with ❤️ by the DevAgentic team
- **Founded**: December 26, 2024
- **Address**: Lytchett House, 13 Freeland Park, Wareham Road, Poole, Dorset, BH16 6FA, United Kingdom
