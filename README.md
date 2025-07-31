# MindEase

MindEase is an innovative AI-powered mental health chatbot designed to provide personalized emotional support, stress management techniques, and comprehensive well-being assistance. Developed by **Masoom Kumar Choudhury**, this project demonstrates advanced full-stack development skills and leverages cutting-edge AI technology to create meaningful mental health solutions.

## 🔹 Project Overview

MindEase showcases modern web development practices by utilizing **Google's Gemini AI** to deliver intelligent, context-aware responses to users seeking mental health support. The application features a sophisticated **React-based frontend** with clean, responsive design principles, demonstrating proficiency in modern JavaScript frameworks and UI/UX development.

**Technical Highlights:**
- **Frontend Architecture**: Built with React 18, leveraging hooks and modern component patterns
- **AI Integration**: Direct API communication with Google Gemini AI for real-time responses
- **Performance Optimization**: Serverless architecture eliminating backend dependencies
- **Security Implementation**: Environment-based API key management and secure data handling
- **Development Workflow**: Modern tooling with Vite, ESLint, and Prettier for code quality

## ✨ Key Features & Technical Skills Demonstrated

- **AI-Powered Conversational Interface** – Intelligent emotional support system with context-aware responses
- **Google Gemini AI Integration** – Advanced API integration showcasing external service communication
- **Modern React Development** – Component-based architecture with hooks, context API, and state management
- **Responsive Web Design** – Mobile-first approach with CSS3 and modern styling techniques
- **API Security & Environment Management** – Secure handling of sensitive data and API keys
- **Performance Optimization** – Efficient rendering and minimal bundle size with Vite build system
- **Code Quality Standards** – ESLint configuration, Prettier formatting, and clean code practices
- **Version Control & Deployment** – Git workflow and GitHub Pages deployment setup

## 🛠️ Technology Stack

**Frontend:**
- React 18 with JSX
- Modern JavaScript (ES6+)
- CSS3 with responsive design
- Lucide React for icons
- Marked for markdown parsing

**Development Tools:**
- Vite for fast development and building
- ESLint for code linting
- Prettier for code formatting
- GitHub Pages for deployment

**AI & APIs:**
- Google Generative AI (Gemini)
- Environment variable management
- Secure API communication

## 🔧 Quick Start for GitHub & Vercel

### Step 1: Create GitHub Repository
1. Create a new repository on GitHub named `mindease`
2. Initialize with this project:
   ```bash
   git init
   git add .
   git commit -m "Initial commit: MindEase AI Mental Health Chatbot"
   git branch -M main
   git remote add origin https://github.com/your-username/mindease.git
   git push -u origin main
   ```

### Step 2: Deploy to Vercel
1. Visit [vercel.com](https://vercel.com) and sign in with GitHub
2. Click "New Project" → Import your `mindease` repository
3. Add environment variable: `GEMINI_API_KEY` = your API key
4. Deploy! Your app will be live at `https://mindease-your-username.vercel.app`

## 📌 Local Development Setup

### 1️⃣ Prerequisites

Ensure you have the following installed:
- **Node.js** (Latest LTS version recommended)
- **npm** or **yarn**
- **Git** for version control

### 2️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/mindease.git
cd mindease
```

*Note: Replace `your-username` with your actual GitHub username*

### 3️⃣ Install Dependencies

```bash
npm install
```

### 4️⃣ Configure Environment Variables

Create a `.env.local` file in the project root:

```ini
GEMINI_API_KEY=your-gemini-api-key-here
```

**To get your Gemini API key:**
1. Visit [Google AI Studio](https://makersuite.google.com/app/apikey)
2. Create a new API key
3. Copy and paste it into your `.env.local` file

### 5️⃣ Configure AI Model (Optional)

Update the model configuration in `src/config/gemini.js` if needed:

```javascript
const model = genAI.getGenerativeModel({
  model: "gemini-pro", // or your preferred model
});
```

### 6️⃣ Run the Development Server

```bash
npm run dev
```

Access the application at [`http://localhost:5173`](http://localhost:5173)

### 7️⃣ Build for Production

```bash
npm run build
```

## 🚀 Deployment

### Vercel Deployment (Recommended)

1. **Push to GitHub**:
   ```bash
   git add .
   git commit -m "Initial commit - MindEase AI Chatbot"
   git push origin main
   ```

2. **Deploy to Vercel**:
   - Visit [vercel.com](https://vercel.com) and sign in with GitHub
   - Click "New Project" and import your repository
   - Configure environment variables:
     - Add `GEMINI_API_KEY` with your API key value
   - Deploy automatically

3. **Environment Variables Setup**:
   - In Vercel dashboard → Project Settings → Environment Variables
   - Add: `GEMINI_API_KEY` = `your-actual-api-key`

### Alternative: GitHub Pages

```bash
npm run deploy
```

### Local Development

```bash
npm run dev
```

**Live Demo**: [mindease-ai.vercel.app](https://mindease-ai.vercel.app) *(Update with your actual URL)*

## 💡 Development Approach & Problem Solving

This project demonstrates several key development competencies:

**1. User-Centered Design**
- Intuitive chat interface prioritizing user experience
- Responsive design ensuring accessibility across devices
- Clean, calming visual design appropriate for mental health context

**2. Technical Architecture**
- Modular component structure for maintainability
- Context API for efficient state management
- Environment-based configuration for different deployment stages

**3. Performance Considerations**
- Optimized bundle size with tree shaking
- Lazy loading and efficient re-rendering
- Minimal API calls with intelligent caching strategies

**4. Security Best Practices**
- Secure API key management
- Input sanitization and validation
- Safe handling of user data

## 🔧 Code Quality & Standards

- **ESLint Configuration**: Enforces consistent coding standards
- **Prettier Integration**: Automated code formatting
- **Component Architecture**: Reusable, maintainable React components
- **Git Workflow**: Clean commit history with meaningful messages
- **Documentation**: Comprehensive README and inline code comments

## 🎯 Future Enhancements

Potential improvements that demonstrate forward-thinking development:
- User authentication and session management
- Chat history persistence with local storage
- Advanced AI prompt engineering for better responses
- Integration with mental health resources and crisis support
- Progressive Web App (PWA) capabilities
- Accessibility improvements (WCAG compliance)

## 📊 Project Metrics

- **Lines of Code**: ~500+ (excluding dependencies)
- **Components**: 5+ reusable React components
- **Dependencies**: Carefully selected, minimal footprint
- **Build Time**: <30 seconds
- **Bundle Size**: Optimized for fast loading

## 🔍 Code Quality & Best Practices

This project demonstrates professional development standards:

- **Clean Architecture**: Modular React components with separation of concerns
- **Modern JavaScript**: ES6+ features, async/await, and functional programming
- **Code Standards**: ESLint and Prettier for consistent formatting
- **Security**: Environment variables for API key management
- **Performance**: Optimized builds and efficient rendering
- **Responsive Design**: Mobile-first approach with CSS Grid and Flexbox

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Developer

**Masoom Kumar Choudhury** - Full Stack Developer

This project showcases expertise in:
- React.js and modern JavaScript development
- AI/ML integration with Google Gemini API
- Responsive web design and user experience
- API security and environment management
- Modern development workflows and deployment

**Portfolio Project** - Demonstrating technical skills for internship applications

---

*This project demonstrates proficiency in React, JavaScript, AI integration, and modern web development practices suitable for internship and entry-level developer positions.*