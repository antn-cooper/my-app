# My React App

[![Deploy to GitHub Pages](https://github.com/YOUR_GITHUB_USERNAME/my-app/actions/workflows/deploy.yml/badge.svg)](https://github.com/YOUR_GITHUB_USERNAME/my-app/actions/workflows/deploy.yml)

A React app built with Vite and deployed to GitHub Pages using GitHub Actions.

## Setup and Development

### Local Development

1. Clone the repository:

   ```
   git clone https://github.com/YOUR_GITHUB_USERNAME/my-app.git
   cd my-app
   ```

2. Install dependencies:

   ```
   npm install
   ```

3. Start the development server:
   ```
   npm run dev
   ```

### Docker Development

1. Run the application using Docker Compose:

   ```
   docker-compose up
   ```

2. Access the application at [http://localhost:5173](http://localhost:5173)

## Deployment

The application is automatically deployed to GitHub Pages when changes are pushed to the main branch.

Manual deployment can be triggered by running:

```
npm run deploy
```

## Configuration

- **Vite**: Configured with a base path for GitHub Pages in `vite.config.js`
- **Docker**: Development environment with hot reload using volume mounts
- **GitHub Actions**: Automated build and deployment workflow

## Technologies Used

- React
- Vite
- Docker
- GitHub Actions
- GitHub Pages

# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript and enable type-aware lint rules. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
