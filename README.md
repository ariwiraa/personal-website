# Backend Developer Portfolio

A modern, responsive portfolio website built with Vue.js and Tailwind CSS, showcasing backend development skills and projects.

## Features

- **Modern Design**: Clean, professional interface with gradient backgrounds
- **Responsive Layout**: Mobile-first approach with seamless desktop experience
- **Interactive Navigation**: Smooth scrolling with active section indicators and progress bar
- **Animated Elements**: Smooth transitions, hover effects, and fade-in animations
- **Professional Sections**: Hero, About, Skills, Projects, Contact, and Footer
- **Social Integration**: Direct links to GitHub, LinkedIn, and email
- **Downloadable Resume**: PDF version available for download
- **Modern UI Components**: Cards, gradients, and interactive elements
- **Accessibility**: Proper ARIA labels and keyboard navigation support
- **Performance Optimized**: Fast loading with Vite build system

## Tech Stack

- **Frontend Framework**: Vue.js 3 (Composition API)
- **Styling**: Tailwind CSS with custom gradients
- **Build Tool**: Vite
- **Icons**: Heroicons & Custom SVG icons
- **UI Components**: Headless UI for Vue
- **Router**: Vue Router 4

## Portfolio Sections

### 🏠 Hero Section
- Animated avatar with floating rings and pulse effects
- Professional introduction with gradient typography
- Status indicator showing availability
- Call-to-action buttons for resume and contact
- Background decorative elements with blur effects
- Statistics showcase (projects, experience, technologies)
- Scroll indicator for better UX

### 👨‍💻 About Section
- Professional summary with gradient headers
- Experience level cards with hover animations
- Technical specialization highlights
- Interactive stat cards with icons
- Modern card-based layout with shadows

### 🛠️ Skills Section
- **Backend Languages**: Java, Go with visual icons
- **Frameworks**: Spring Boot, Gin Framework
- **Databases**: PostgreSQL, MySQL
- **Tools**: Git version control
- Interactive skill cards with hover effects
- Technology icons and descriptions
- Organized by categories (Languages, Frameworks, Databases)

### 🚀 Projects Section
- Featured project showcases with preview cards
- Technology stack tags for each project
- GitHub repository links
- Project descriptions and key features
- Hover animations and visual effects

### 📞 Contact Section
- Direct contact cards (Email, GitHub, LinkedIn)
- Social media integration with tooltips
- Call-to-action section
- Professional contact information
- Interactive hover effects

### 🔗 Footer Section
- Brand information with logo
- Social media links with icons
- "Back to Top" functionality
- Professional status indicator
- Gradient background with decorative patterns

## Quick Start

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn

### Installation

1. **Clone the repository**
   ```bash
   git clone <your-repo-url>
   cd portfolio
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

## Customization

### Personal Information
Update the following components:
- **HeroSection.vue**: Update name, title, and professional summary
- **AboutSection.vue**: Modify experience details and specializations
- **SkillsSection.vue**: Add/remove technologies and skill levels
- **ProjectsSection.vue**: Replace with your actual projects and GitHub links
- **ContactSection.vue**: Update email address and social media URLs
- **FooterSection.vue**: Modify brand information and contact details

### Resume PDF
Place your resume PDF file in the `public` folder and update the download link in HeroSection.vue

### Styling Customization
- Colors can be modified in `tailwind.config.js`
- Gradient combinations are defined in component styles
- Animation timings and effects can be adjusted in individual components

### Content Management
Each section is a separate Vue component for easy maintenance:
- `src/components/HeroSection.vue` - Landing section
- `src/components/AboutSection.vue` - Professional summary
- `src/components/SkillsSection.vue` - Technical skills
- `src/components/ProjectsSection.vue` - Project showcase
- `src/components/ContactSection.vue` - Contact information
- `src/components/FooterSection.vue` - Footer with links

## Key Features

### Performance
- **Vite Build System**: Lightning-fast development and optimized production builds
- **SVG Icons**: Scalable vector graphics for crisp visuals
- **Optimized Assets**: Minified CSS and JavaScript
- **Smooth Animations**: CSS transitions and transforms
- **Efficient Routing**: Vue Router for SPA navigation

### User Experience
- **Smooth Scrolling**: Enhanced navigation between sections
- **Progress Indicator**: Visual scroll progress in navigation
- **Active Section Detection**: Automatic highlighting of current section
- **Mobile-First Design**: Responsive across all device sizes
- **Interactive Elements**: Hover effects and micro-interactions

### Modern Design
- **Gradient Backgrounds**: Beautiful color transitions
- **Card-Based Layout**: Clean, organized content presentation
- **Typography Hierarchy**: Clear information structure
- **Consistent Spacing**: Professional layout system
- **Visual Feedback**: Interactive states and animations

### Accessibility
- **ARIA Labels**: Screen reader support
- **Keyboard Navigation**: Full keyboard accessibility
- **Focus Management**: Clear focus indicators
- **Semantic HTML**: Proper document structure
- **Color Contrast**: WCAG compliant color schemes

## Project Structure

```
src/
├── components/
│   ├── HeroSection.vue      # Landing section with intro
│   ├── AboutSection.vue     # Professional summary
│   ├── SkillsSection.vue    # Technical skills showcase
│   ├── ProjectsSection.vue  # Featured projects
│   ├── ContactSection.vue   # Contact information
│   ├── FooterSection.vue    # Footer with links
│   ├── Navigation.vue       # Main navigation bar
│   └── Home.vue            # Main page component
├── App.vue                 # Root component
├── main.js                # Application entry point
└── style.css              # Global styles
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Deployment

This project can be deployed to:
- **Netlify**: Drag and drop the `dist` folder
- **Vercel**: Connect your GitHub repository
- **GitHub Pages**: Use GitHub Actions for automatic deployment
- **Any static hosting service**: Upload the `dist` folder

Build command: `npm run build`

## License

MIT License - feel free to use this template for your own portfolio!

## Contributing

Contributions are welcome! Please feel free to submit issues and enhancement requests.

---

**Built with ❤️ using Vue.js and Tailwind CSS**
