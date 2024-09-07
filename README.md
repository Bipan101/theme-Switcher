# Theme Switcher

A simple Theme switcher project implemented using React, Context API, and Tailwind CSS, built with Vite.

## Features
- Toggle between light and dark themes for a specific div element.
- State management using React's Context API.
- Styled with Tailwind CSS for responsive and easy styling.
- Fast development build using Vite.

## Tech Stack
- React: Component-based UI development.
- Context API: For managing theme state globally.
- Tailwind CSS: Utility-first CSS framework for styling.
- Vite: A fast bundler and build tool for modern web projects.

## Installation

1. Clone the repository:
 ```bash
 git clone https://github.com/Bipan101/theme-Switcher.git
```
2. Navigate to the project directory:
```bash
cd theme-Switcher
```
3. Install the dependencies:
```bash
npm install
```
4. Start the development server:
```bash
npm run dev
```
## Usage
- The app contains a div element with a toggle button to switch between light and dark themes.
- The theme context is managed globally using the Context API, so the theme switch is accessible throughout the app.

### Folder Structure
```bash
theme-switcher/
│
├── public/                
├── src/                   
│   ├── components/        
│   │   ├── Card.jsx       
│   │   └── ThemeBtn.jsx   
│   ├── context/           
│   │   └── Theme.js       
│   └── App.jsx            
│
├── index.html             
├── package.json           
├── tailwind.config.js     
└── vite.config.js         

