# Shiguang

A timeline-based progressive web application.

## Project Overview

Shiguang is a web application focused on timeline visualization, designed with modern PWA architecture to support offline access and a native app-like user experience.

## Key Features

- 📅 **Timeline Display** - Present content in a timeline format  
- ⏰ **Time Markers** - Interactive time-based controls via circular buttons  
- 📱 **PWA Support** - Installable to the home screen with offline access  
- 💧 **Watermark Feature** - Protect content copyright  

## Technical Features

- Progressive Web App (PWA)  
- Service Worker caching strategy  
- Responsive design  
- Offline access support  

## Quick Start

### Prerequisites

- Modern browser (Chrome, Firefox, Edge, etc.)  
- Local server (required for PWA functionality testing)

### Installation & Deployment

1. Clone the project locally:
```bash
git clone https://gitee.com/dlin321603776/shiguang.git
```

2. Run with a local server:
```bash
# Using Python
python -m http.server 8000

# Or using Node.js
npx http-server -p 8000
```

3. Access in your browser: `http://localhost:8000`

### PWA Installation

- Visit the site in a supported browser  
- Click the "Add to Home Screen" button  
- Use the app like a native application  

## Project Structure

```
shiguang/
├── index.html      # Main page
├── manifest.json   # PWA configuration file
├── sw.js           # Service Worker
├── LICENSE         # License
└── .gitignore      # Git ignore configuration
```

## License

This project is open-sourced under the MIT License.