# Vite + React + GitHub Actions Demo

[![Deploy to GitHub Pages](https://github.com/Sugatraj/vite-gh-actions/actions/workflows/deploy.yml/badge.svg)](https://github.com/Sugatraj/vite-gh-actions/actions/workflows/deploy.yml)
[![GitHub license](https://img.shields.io/github/license/Sugatraj/vite-gh-actions)](https://github.com/Sugatraj/vite-gh-actions/blob/main/LICENSE)
[![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=flat&logo=vite&logoColor=white)](https://vitejs.dev/)
[![React](https://img.shields.io/badge/react-%2320232a.svg?style=flat&logo=react&logoColor=%2361DAFB)](https://reactjs.org/)
[![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=flat&logo=githubactions&logoColor=white)](https://github.com/features/actions)

A production-ready template for deploying Vite + React applications to GitHub Pages using GitHub Actions. This repository provides a complete CI/CD workflow with GitHub Actions YAML configuration for automated builds and deployments.

Keywords: vite-template, github-actions-deployment, react-vite-app, github-pages-deployment, vite-github-actions, yaml-workflow

[🌐 Live Demo](https://sugatraj.github.io/vite-gh-actions/) | [📖 Documentation](#-features) | [🚀 Quick Start](#%EF%B8%8F-local-development)

This project demonstrates a modern React application setup using Vite as the build tool, with automated deployment to GitHub Pages using GitHub Actions. It showcases best practices for React development and CI/CD workflows.

## 🚀 Features

- ⚡️ **Lightning Fast Development** with [Vite](https://vitejs.dev/)
- ⚛️ **React 19** with latest features
- 🎨 **Bootstrap 5** for responsive UI components
- 📦 **Automated Deployment** to GitHub Pages
- 🔍 **ESLint** for code quality
- 🔄 **Hot Module Replacement (HMR)**
- 📱 **Responsive Design** out of the box

## 🛠️ Tech Stack

- **Frontend Framework:** React 19
- **Build Tool:** Vite 6
- **UI Framework:** Bootstrap 5.3
- **Deployment:** GitHub Pages
- **CI/CD:** GitHub Actions
- **Package Manager:** npm
- **Code Quality:** ESLint

## 🏃‍♂️ Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/Sugatraj/vite-gh-actions.git
   cd vite-gh-actions
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

## 🔄 GitHub Actions Workflow

The project uses GitHub Actions for automated deployment to GitHub Pages. The workflow:

1. Triggers on:
   - Push to main branch
   - Manual workflow dispatch

2. Build Process:
   - Checks out the code
   - Sets up Node.js 18
   - Installs dependencies
   - Builds the project
   - Configures GitHub Pages
   - Uploads build artifacts

3. Deployment:
   - Automatically deploys to GitHub Pages
   - Provides deployment URL

### 🔧 Troubleshooting Deployment

If you encounter deployment issues:

1. Ensure your repository settings have GitHub Pages enabled
2. Check that the deployment workflow has necessary permissions
3. Verify that the build process completes successfully
4. Confirm that the `homepage` field in `package.json` matches your repository URL

## 📝 Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint
- `npm run deploy` - Deploy to GitHub Pages

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is open source and available under the MIT License.

## 🎯 Why This Template?

- ✅ **Zero Configuration Deployment**: Just push your code and it's live
- ✅ **Production Optimized**: Built-in optimization for production builds
- ✅ **CI/CD Best Practices**: Implements GitHub Actions workflow best practices
- ✅ **Automated Workflow**: Complete YAML configuration for GitHub Actions
- ✅ **SEO Friendly**: Optimized for search engine visibility
- ✅ **Community Ready**: Well-documented for easy contributions

## 📚 Related Resources

- [Vite Documentation](https://vitejs.dev/)
- [GitHub Actions Documentation](https://docs.github.com/en/actions)
- [GitHub Pages Deployment Guide](https://docs.github.com/en/pages)
- [React Documentation](https://react.dev/)
