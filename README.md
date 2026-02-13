# Valentine's Proposal Website

An interactive, touch-enabled web experience built with React, Vite, and GSAP animations.

## Tech Stack

- **React 18** - UI library
- **Vite** - Build tool and dev server
- **GSAP** - Advanced animations
- **Tailwind CSS** - Utility-first CSS framework
- **Custom Gesture Handling** - Touch-enabled interactions

## Getting Started

### Prerequisites

- Node.js 16+ 
- npm or yarn

### Installation

1. Clone the repository
2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:5173`

## Building for Production

```bash
npm run build
```

The optimized build will be in the `dist/` directory.

## Preview Production Build

```bash
npm run preview
```

## Project Structure

```
├── src/
│   ├── App.jsx          # Main application component
│   ├── main.jsx         # React entry point
│   └── index.css        # Global styles with Tailwind
├── index.html           # HTML template
├── vite.config.js       # Vite configuration
├── tailwind.config.js   # Tailwind CSS configuration
└── package.json         # Project dependencies
```

## Features

- Smooth panel animations using GSAP
- Touch manipulation support for mobile devices
- Responsive design with Tailwind CSS
- Fast development with Vite's HMR

## License

MIT