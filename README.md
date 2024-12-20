# CodeAnt AI: Frontend Developer Intern Hiring Assignment  

## Overview  
**CodeAnt AI** is a Y Combinator-backed startup revolutionizing the code quality and security industry. By leveraging AI-driven and deterministic fixes, we simplify coding, making it cleaner, safer, and more efficient. Trusted by leading unicorns and supported by top Silicon Valley investors, CodeAnt AI tackles complex problems and pushes the boundaries of innovation.  


## Installation  

Follow these steps to set up the project locally:

1. **Clone the repository**:  
   ```bash  
   git clone https://github.com/31adityakumar/CodeAnt-AI 
   cd CodeAnt-AI

2. **Install dependencies**:  
   ```bash  
   yarn install
   ```  

3. **Start the development server**:  
   ```bash  
   yarn dev  
   ```  
   
---

## Technologies Used  
- **ReactJS**: For building the user interface.  
- **TypeScript**: For adding static typing and improving code quality.  
- **Tailwind CSS**: For utility-first styling and rapid UI development.  
- **Vite**: For fast development and build process.  

---

## Features  
- Fully responsive design, optimized for different screen sizes.  
- Accurate implementation of the Figma design.  
- Clean and modular code for scalability and maintainability.  

# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
export default tseslint.config({
  languageOptions: {
    // other options...
    parserOptions: {
      project: ['./tsconfig.node.json', './tsconfig.app.json'],
      tsconfigRootDir: import.meta.dirname,
    },
  },
})
```

- Replace `tseslint.configs.recommended` to `tseslint.configs.recommendedTypeChecked` or `tseslint.configs.strictTypeChecked`
- Optionally add `...tseslint.configs.stylisticTypeChecked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and update the config:

```js
// eslint.config.js
import react from 'eslint-plugin-react'

export default tseslint.config({
  // Set the react version
  settings: { react: { version: '18.3' } },
  plugins: {
    // Add the react plugin
    react,
  },
  rules: {
    // other rules...
    // Enable its recommended rules
    ...react.configs.recommended.rules,
    ...react.configs['jsx-runtime'].rules,
  },
})
```
