[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=19932309&assignment_repo_type=AssignmentRepo)
# Deployment and DevOps for MERN Applications

This assignment focuses on deploying a full MERN stack application to production, implementing CI/CD pipelines, and setting up monitoring for your application.

## Assignment Overview

You will:
1. Prepare your MERN application for production deployment
2. Deploy the backend to a cloud platform
3. Deploy the frontend to a static hosting service
4. Set up CI/CD pipelines with GitHub Actions
5. Implement monitoring and maintenance strategies

## Getting Started

1. Accept the GitHub Classroom assignment invitation
2. Clone your personal repository that was created by GitHub Classroom
3. Follow the setup instructions in the `Week7-Assignment.md` file
4. Use the provided templates and configuration files as a starting point

## Files Included

- `Week7-Assignment.md`: Detailed assignment instructions
- `.github/workflows/`: GitHub Actions workflow templates
- `deployment/`: Deployment configuration files and scripts
- `.env.example`: Example environment variable templates
- `monitoring/`: Monitoring configuration examples

## Requirements

- A completed MERN stack application from previous weeks
- Accounts on the following services:
  - GitHub
  - MongoDB Atlas
  - Render, Railway, or Heroku (for backend)
  - Vercel, Netlify, or GitHub Pages (for frontend)
- Basic understanding of CI/CD concepts

## Deployment Platforms

### Backend Deployment Options
- **Render**: Easy to use, free tier available
- **Railway**: Developer-friendly, generous free tier
- **Heroku**: Well-established, extensive documentation

### Frontend Deployment Options
- **Vercel**: Optimized for React apps, easy integration
- **Netlify**: Great for static sites, good CI/CD
- **GitHub Pages**: Free, integrated with GitHub

## CI/CD Pipeline

The assignment includes templates for setting up GitHub Actions workflows:
- `frontend-ci.yml`: Tests and builds the React application
- `backend-ci.yml`: Tests the Express.js backend
- `frontend-cd.yml`: Deploys the frontend to your chosen platform
- `backend-cd.yml`: Deploys the backend to your chosen platform

## ✅ Submission & Evidence of Completion

All objectives for Week 7 have been met. See below for evidence and documentation:

### ✔️ Deployment URLs
- **Frontend (React) Live URL:** [https://eduedge.netlify.app](https://eduedge.netlify.app)
- **Backend (Express API) Live URL:** [https://homework-helper-backend.onrender.com](https://homework-helper-backend.onrender.com)

### ✔️ CI/CD Pipeline
- Automated with GitHub Actions (`.github/workflows/mern-ci-cd.yml`)
- Runs tests, linting, builds, and deploys both frontend and backend on every push to `main`
- Health checks run after deployment

#### CI/CD Pipeline Screenshots
![CI/CD Pipeline Screenshot 1](screenshots/cicd-1.png)
![CI/CD Pipeline Screenshot 2](screenshots/cicd-2.png)

### ✔️ Environment Variables
- Templates provided: `client/.env.example`, `server/.env.example`
- All sensitive keys and URLs are managed via environment variables and GitHub secrets

### ✔️ Monitoring & Health Checks
- Health check endpoints implemented and tested (`/api/health`)
- Automated uptime checks in CI/CD pipeline
- (Optional) Error tracking and performance monitoring can be set up with Sentry or similar

### ✔️ Maintenance & Documentation
- Regular updates and patches planned
- Database backups and rollback procedures documented
- This README.md contains all deployment and maintenance instructions

### ✔️ Objective Checklist
- [x] Production-ready React frontend (build, code splitting, env vars)
- [x] Production-ready Express backend (error handling, security, logging, env vars)
- [x] MongoDB Atlas setup and connection pooling
- [x] Backend deployed to Render/Railway/Heroku
- [x] Frontend deployed to Vercel/Netlify/GitHub Pages
- [x] CI/CD with GitHub Actions (test, lint, build, deploy)
- [x] Health checks and monitoring
- [x] Environment variable templates
- [x] Documentation and screenshots

## Resources

- [GitHub Actions Documentation](https://docs.github.com/en/actions)
- [MongoDB Atlas Documentation](https://docs.atlas.mongodb.com/)
- [Render Documentation](https://render.com/docs)
- [Railway Documentation](https://docs.railway.app/)
- [Vercel Documentation](https://vercel.com/docs)
- [Netlify Documentation](https://docs.netlify.com/)