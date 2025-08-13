# Educational Platform

A modern and comprehensive React-based educational platform template built with TypeScript and Vite. Perfect for online course providers, educational institutions, and e-learning businesses.

## Project Overview

This template provides a complete solution for creating sophisticated educational websites with course management, instructor profiles, event listings, and e-commerce functionality. Built with modern web technologies and optimized for performance.

## Technologies Used

### Frontend Framework
- **React**: 18.3.1
- **React DOM**: 18.3.1
- **TypeScript**: 5.5.3 (Type safety and better development experience)
- **React Router DOM**: 6.26.1 (Client-side routing)

### Build Tools & Development
- **Vite**: 5.4.1 (Fast build tool and dev server)
- **ESLint**: 9.9.0 (Code linting)
- **Sass**: 1.77.8 (CSS preprocessing)

### UI & Styling
- **Bootstrap**: 5.3.3 (CSS framework)
- **Animate.css**: 4.1.1 (CSS animations)
- **WOW.js**: 1.2.2 (Scroll animations)

### React Components & Libraries
- **React Slick**: 0.30.2 (Carousel/slider component)
- **React Modal Video**: 2.0.2 (Video modal functionality)
- **React Range**: 1.10.0 (Range input component)
- **React CountUp**: 6.5.3 (Animated counters)
- **React Circular ProgressBar**: 2.1.0 (Progress indicators)
- **React Timer Hook**: 3.0.8 (Timer functionality)
- **React Use**: 17.6.0 (React hooks utilities)
- **React Intersection Observer**: 9.13.0 (Scroll detection)

### Third-party Integrations
- **Supabase**: Ready-to-use backend integration (configured but optional)

## Project Structure

```
├── src/
│   ├── components/           # Feature-based components
│   │   ├── homes/           # Multiple home page variants
│   │   │   ├── home/        # Home page layout 1
│   │   │   ├── home-2/      # Home page layout 2
│   │   │   ├── home-3/      # Home page layout 3
│   │   │   ├── home-4/      # Home page layout 4
│   │   │   └── home-5/      # Home page layout 5
│   │   ├── about/           # About page components
│   │   ├── courses/         # Course-related components
│   │   ├── courses-details/ # Course detail pages
│   │   ├── instructor/      # Instructor components
│   │   ├── event/           # Event listing components
│   │   ├── shop/            # E-commerce components
│   │   ├── news/            # Blog/news components
│   │   └── ...
│   ├── layouts/             # Layout components
│   │   ├── headers/         # Header variants
│   │   └── footers/         # Footer variants
│   ├── common/              # Shared/common components
│   │   ├── Count.tsx        # Counter component
│   │   ├── Timer.tsx        # Timer component
│   │   ├── ScrollToTop.tsx  # Scroll utilities
│   │   └── ...
│   ├── ui/                  # UI components
│   │   ├── InputRange.tsx   # Range input
│   │   └── NiceSelect.tsx   # Select dropdown
│   ├── data/                # Static data
│   ├── hooks/               # Custom React hooks
│   ├── types/               # TypeScript type definitions
│   ├── integrations/        # Third-party integrations
│   │   └── supabase/       # Supabase configuration
│   └── styles/              # Sass stylesheets
├── public/                  # Static assets
│   └── assets/              # Images, fonts, CSS files
└── documentation/           # Project documentation
```

## Page Functionality

### Home Pages (5 Variants)
- **Home 1**: Classic layout with hero section, courses, and testimonials
- **Home 2**: Modern design with featured courses and team section
- **Home 3**: Minimal design with focus on content
- **Home 4**: Corporate style with emphasis on achievements
- **Home 5**: Creative layout with unique animations

### Core Pages
- **About**: Company information with team and achievements
- **Courses**: Course catalog with filtering and search
- **Course Details**: Individual course pages with curriculum and reviews
- **Instructors**: Teacher profiles and expertise
- **Events**: Educational events and webinars
- **News/Blog**: Educational articles and updates
- **Contact**: Contact information and inquiry forms

### E-commerce Features
- **Shop**: Product catalog for educational materials
- **Shop Details**: Individual product pages
- **Shopping Cart**: Cart management
- **Checkout**: Purchase flow

### Additional Features
- **User Registration/Login**: User account management
- **FAQ**: Frequently asked questions
- **Gallery**: Image showcase
- **Pricing**: Course pricing information
- **404 Error**: Custom error page

## Getting Started

### Prerequisites
- Node.js (version 16 or higher)
- npm or yarn package manager

### Installation

1. Clone or download the project
2. Navigate to the project directory
3. Install dependencies:
```bash
npm install
```

### Development

Start the development server:
```bash
npm run dev
```

The application will open at `http://localhost:8080`

### Build for Production

Create a production build:
```bash
npm run build
```

### Linting

Run ESLint:
```bash
npm run lint
```

### Preview Production Build

Preview the production build:
```bash
npm run preview
```

## Features

### ✅ Multiple Design Variants
- 5 different home page layouts
- Multiple header and footer styles
- Flexible component system

### ✅ Course Management
- Course listing with advanced filtering
- Detailed course pages with curriculum
- Instructor profiles and ratings
- Course reviews and testimonials

### ✅ E-commerce Integration
- Product catalog for educational materials
- Shopping cart functionality
- Checkout process
- Order management

### ✅ Event Management
- Event listings and details
- Event registration functionality
- Calendar integration
- Event categories

### ✅ Content Management
- Blog/news system
- FAQ section
- Gallery showcase
- Newsletter subscription

### ✅ Advanced UI Components
- Animated counters and progress bars
- Video modal integration
- Range sliders for filtering
- Carousel/slider components
- Timer components for countdowns

### ✅ Performance Optimized
- TypeScript for type safety
- Vite for fast development and builds
- Code splitting and lazy loading
- Optimized assets and images

### ✅ Integration Ready
- Supabase backend integration configured
- Bootstrap responsive framework
- Modern animation libraries
- SEO-friendly structure

## Customization

### Styling
The template uses Sass for styling with Bootstrap integration:
- `src/styles/` - Main stylesheets
- `public/assets/scss/` - Component-specific styles
- Bootstrap variables can be customized

### Components
- All components are modular and reusable
- TypeScript interfaces for type safety
- Easy to extend and customize

### Content
Update content by modifying:
- Component files in `src/components/`
- Data files in `src/data/`
- Static assets in `public/assets/`

### Configuration
- Vite configuration in `vite.config.ts`
- TypeScript configuration in `tsconfig.json`
- ESLint rules in `eslint.config.js`

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance

- Fast development with Vite HMR
- Optimized production builds
- Lazy loading for better performance
- Code splitting for smaller bundles
- Asset optimization

## License

This template is ready for commercial and personal use.
