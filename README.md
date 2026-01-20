# Portfolio Website

A modern, responsive portfolio website showcasing projects, skills, experience, and recommendations. Built with Next.js and React.

## 🚀 Technologies & Skills Used

### Core Framework & Language
- **Next.js 16.1.1** - React framework for production
  - App Router architecture
  - Server-side rendering (SSR)
  - Static site generation (SSG)
  - Client-side navigation
- **React 19.2.3** - UI library
  - Functional components with hooks
  - Context API for state management
  - Component composition
- **TypeScript 5** - Type-safe JavaScript
  - Type definitions
  - Interface definitions
  - Type checking

### Styling & UI
- **CSS3** - Custom styling
  - CSS Grid for layouts
  - Flexbox for component alignment
  - CSS animations and transitions
  - Responsive design with media queries
  - Custom scrollbars
  - Gradient backgrounds
  - Box shadows and visual effects
- **Tailwind CSS 4** - Utility-first CSS framework (via PostCSS)

### State Management
- **React Context API** - Global state management
  - SectionContext for managing collapsible sections
  - Provider pattern implementation
- **React Hooks**
  - `useState` - Component state
  - `useEffect` - Side effects and lifecycle
  - `useMemo` - Performance optimization
  - `useRef` - DOM references

### Features & Functionality

#### UI/UX Features
- **Collapsible Sections** - Expandable/collapsible content sections
- **Smooth Animations** - CSS transitions and transforms
- **Scroll Animations** - RevealOnScroll component for scroll-triggered animations
- **Modal Popups** - Project detail modals with full descriptions
- **Responsive Design** - Mobile-first, adaptive layouts
- **Interactive Navigation** - Smooth scrolling and hash navigation

#### Project Features
- **Project Filtering** - Category-based filtering (All, Mobile, PC Games, VR)
- **Dynamic Grid Layout** - CSS Grid with auto-fill for responsive project cards
- **Video Embedding** - YouTube and Vimeo video support
- **Thumbnail Display** - Image thumbnails with clickable overlays
- **Project Cards** - Dynamic sizing based on content
- **Category Badges** - Technology tags display

#### Data Management
- **JSON Data Files** - Structured data storage
  - `projects.json` - Project information
  - `skills.json` - Skills and technologies
  - `experience.json` - Work experience
  - `recommendations.json` - Client testimonials
  - `education.json` - Educational background

### Development Tools
- **ESLint** - Code linting and quality
- **TypeScript Compiler** - Type checking
- **Next.js Dev Server** - Hot module replacement
- **Babel Plugin React Compiler** - React optimization

### Web Technologies
- **HTML5** - Semantic markup
- **CSS3** - Advanced styling
  - CSS Variables
  - CSS Grid
  - Flexbox
  - Animations & Transitions
  - Media Queries
- **JavaScript (ES6+)** - Modern JavaScript features
  - Arrow functions
  - Destructuring
  - Template literals
  - Async/await
  - Modules

### Browser APIs Used
- **Intersection Observer API** - Scroll animations (via RevealOnScroll)
- **History API** - URL hash management
- **Fetch API** - Data fetching (if needed)
- **Window API** - Browser window operations

### Architecture Patterns
- **Component-Based Architecture** - Reusable React components
- **Context Pattern** - Global state management
- **Props Pattern** - Component communication
- **Custom Hooks** - Reusable logic
- **Separation of Concerns** - Components, data, and styles separated

## 📁 Project Structure

```
portfolio/
├── app/
│   ├── globals.css          # Global styles
│   ├── layout.tsx           # Root layout with providers
│   └── page.tsx             # Main page component
├── components/
│   ├── CollapsibleSection.tsx    # Reusable collapsible section
│   ├── Contact.tsx               # Contact section
│   ├── EducationSection.tsx      # Education display
│   ├── ExperienceSection.tsx     # Work experience
│   ├── Footer.tsx                # Footer component
│   ├── HashNavigation.tsx        # Hash-based navigation
│   ├── Hero.tsx                  # Hero/landing section
│   ├── Navbar.tsx                # Navigation bar
│   ├── ProjectCard.tsx           # Individual project card
│   ├── ProjectsSection.tsx       # Projects grid with filters
│   ├── RecommendationsSection.tsx # Testimonials
│   ├── RevealOnScroll.tsx        # Scroll animation wrapper
│   └── SkillsSection.tsx         # Skills display
├── contexts/
│   └── SectionContext.tsx        # Global section state
├── data/
│   ├── education.json            # Education data
│   ├── experience.json           # Experience data
│   ├── projects.json             # Projects data
│   ├── recommendations.json      # Recommendations data
│   └── skills.json               # Skills data
└── package.json                  # Dependencies
```

## 🎨 Key Features

### 1. Collapsible Sections
- All major sections can be expanded/collapsed
- Clicking navigation tabs opens the corresponding section
- Only one section open at a time
- Smooth animations

### 2. Project Showcase
- Grid layout with category filtering
- Project cards with thumbnails/videos
- Modal popups with full project details
- Technology badges
- Links to demos and videos

### 3. Responsive Design
- Mobile-first approach
- Adaptive grid layouts
- Touch-friendly interactions
- Optimized for all screen sizes

### 4. Interactive Elements
- Hover effects on cards and buttons
- Smooth scrolling navigation
- Animated section reveals
- Modal overlays with backdrop

## 🛠️ Installation & Setup

### Prerequisites
- Node.js 18+ 
- npm or yarn

### Installation Steps

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd portfolio
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Run development server**
   ```bash
   npm run dev
   ```

4. **Build for production**
   ```bash
   npm run build
   ```

5. **Start production server**
   ```bash
   npm start
   ```

## 📝 Configuration

### Environment Variables
No environment variables required for basic functionality.

### Data Management
All data is stored in JSON files in the `data/` directory:
- Edit JSON files to update content
- No database required
- Static data for fast loading

## 🎯 Skills Demonstrated

### Frontend Development
- ✅ React component architecture
- ✅ TypeScript type safety
- ✅ Responsive CSS design
- ✅ Modern JavaScript (ES6+)
- ✅ State management patterns
- ✅ Component composition
- ✅ Performance optimization

### UI/UX Design
- ✅ User interface design
- ✅ User experience optimization
- ✅ Animation and transitions
- ✅ Accessibility considerations
- ✅ Mobile responsiveness

### Web Development
- ✅ Next.js framework
- ✅ Static site generation
- ✅ Client-side routing
- ✅ Hash navigation
- ✅ Modal implementations
- ✅ Form handling

### Code Quality
- ✅ TypeScript for type safety
- ✅ ESLint for code quality
- ✅ Component reusability
- ✅ Clean code practices
- ✅ Separation of concerns

## 📦 Dependencies

### Production Dependencies
- `next` - Next.js framework
- `react` - React library
- `react-dom` - React DOM rendering

### Development Dependencies
- `typescript` - TypeScript compiler
- `@types/node` - Node.js type definitions
- `@types/react` - React type definitions
- `@types/react-dom` - React DOM type definitions
- `eslint` - Code linting
- `eslint-config-next` - Next.js ESLint config
- `tailwindcss` - CSS framework
- `@tailwindcss/postcss` - Tailwind PostCSS plugin
- `babel-plugin-react-compiler` - React compiler

## 🚀 Deployment

The project is configured for static export:
- `output: "export"` in `next.config.js`
- Can be deployed to any static hosting service
- Compatible with Vercel, Netlify, GitHub Pages, etc.

### GitHub Pages Deployment

1. **Enable GitHub Pages**:
   - Go to your repository Settings → Pages
   - Set Source to "GitHub Actions"

2. **Push to GitHub**:
   ```bash
   git add .
   git commit -m "Initial commit"
   git push origin main
   ```

3. **Automatic Deployment**:
   - The `.github/workflows/pages.yml` workflow will automatically build and deploy your site
   - Your site will be available at `https://<username>.github.io/<repository-name>`

4. **Manual Build**:
   ```bash
   npm run build
   ```
   The static files will be in the `out/` directory.

### GitHub Actions CI/CD

The project includes GitHub Actions workflows:
- **Build workflow** (`.github/workflows/deploy.yml`): Runs on push/PR to validate builds
- **Pages workflow** (`.github/workflows/pages.yml`): Automatically deploys to GitHub Pages

Both workflows:
- Use Node.js 20
- Install dependencies with `npm ci`
- Run linting
- Build the project
- Deploy to GitHub Pages (pages workflow only)

## 📄 License

Private project - All rights reserved

## 👤 Author

**Hetal Patel**
- Portfolio: [hetalpateldev.github.io](https://hetalpateldev.github.io)
- LinkedIn: [linkedin.com/in/hetalpatel-unitydeveloper](https://linkedin.com/in/hetalpatel-unitydeveloper)

---

Built with ❤️ using Next.js and React
