# Nova Freelance Agency – DevOps Portfolio Website

A responsive portfolio website developed for the **Advanced Git & DevOps Team Collaboration Assignment**. The project represents a fictional freelance digital agency and demonstrates professional Git collaboration, feature branching, CI/CD automation, and cloud deployment using Vercel.

---

## 👥 Group Information

| Student                 | Student ID          | Role                               |
| ----------------------- | ------------------- | ---------------------------------- |
| **Sewwandi Kodippili**  | **ITBIN-2211-0288** | DevOps Engineer & CI/CD Management |
| **Shanika Udawaththa**  | **ITBIN-2211-0289** | Frontend & UI Development          |
| **Ahinsa Abeywickrama** | **ITBIN-2211-0120** | Backend                            |

---

## 📌 Project Description

**Nova Freelance Agency** is a modern, responsive portfolio website created to showcase the services, skills, projects, and contact information of a freelance digital agency.

The project was developed as a team while following a professional Git and DevOps workflow. The main objectives were to demonstrate:

* Git-based team collaboration
* Feature branch development
* Pull requests and branch merging
* Merge conflict handling
* GitHub Actions CI/CD
* Automated production deployment
* Responsive frontend development
* Clear documentation of individual contributions

---

## 🚀 Live Deployment

🔗 **Nova Freelance Agency:**
https://portfolio-devops-assignment-csg9eo1pp.vercel.app/#contact

The application is deployed on **Vercel** and is publicly accessible.

---

## 🛠️ Technologies Used

* **HTML5** – Website structure
* **CSS3** – Styling and responsive design
* **JavaScript** – Client-side functionality and interactions
* **Git** – Version control
* **GitHub** – Repository and team collaboration
* **GitHub Actions** – Continuous Integration and Deployment
* **Vercel** – Cloud deployment platform

---

## ✨ Features

* Modern freelance agency landing page
* Responsive design for desktop and mobile devices
* Navigation menu
* Services section
* Skills and projects showcase
* Portfolio/project presentation
* Contact section and contact form interaction
* JavaScript-based client-side functionality
* Automated CI workflow
* Automated deployment workflow
* Git-based collaborative development

---

## 🌿 Branch Strategy

The project follows a feature-based Git workflow.

### Main Branches

* `main` – Production-ready code and deployment branch
* `develop` – Integration/development branch
* `feature/*` – Individual developer feature branches

### Feature Branches Used

* `feature/sewwandi` – Sewwandi Kodippili
* `feature/shanika` – Shanika Udawaththa
* `feature/ahinsa` – Ahinsa Abeywickrama

Each team member worked on an individual feature branch before merging changes into the shared project.

---

## 👩‍💻 Individual Contributions

### Sewwandi Kodippili – ITBIN-2211-0288

**Role: DevOps Engineer & CI/CD Management**

* Created and configured the GitHub repository.
* Established the project Git workflow and branch structure.
* Created and managed the `feature/sewwandi` branch.
* Configured GitHub Actions workflows.
* Implemented the CI pipeline using `ci.yml`.
* Configured automated deployment workflows.
* Configured Vercel deployment.
* Managed deployment configuration and environment secrets.
* Investigated and resolved deployment configuration issues.
* Managed repository-level DevOps configuration.
* Updated project documentation and README.
* Coordinated branch merging and integration activities.

### Shanika Udawaththa – ITBIN-2211-0289

**Role: Frontend & UI Development**

* Created the main website frontend structure.
* Developed the HTML page structure.
* Implemented the website layout.
* Designed and developed the CSS styling.
* Implemented responsive design.
* Developed the services section.
* Developed the projects/portfolio sections.
* Improved the overall visual consistency and user interface.
* Contributed frontend code through the `feature/shanika` branch.

### Ahinsa Abeywickrama – ITBIN-2211-0120

**Role: JavaScript & Application Logic**

* Developed the JavaScript functionality for the website.
* Implemented client-side interaction logic.
* Developed contact form interaction functionality.
* Added dynamic browser-side behavior.
* Performed JavaScript code cleanup and validation.
* Contributed application logic through the `feature/ahinsa` branch.

---

## 📁 Project Structure

```text
portfolio-devops-assignment/
│
├── .github/
│   └── workflows/
│       ├── ci.yml
│       ├── deploy.yml
│       ├── deployv.yml
│       └── pages.yml
│
├── src/
│   ├── index.html
│   ├── scripts/
│   │   └── main.js
│   └── styles/
│       └── style.css
│
├── .gitignore
├── package.json
├── vercel.json
└── README.md
```

---

## ⚙️ Setup & Installation

### Prerequisites

Make sure the following are installed:

* Git
* Node.js
* A modern web browser such as Chrome, Edge, or Firefox

### Clone the Repository

```bash
git clone https://github.com/Sewwandi999/portfolio-devops-assignment.git
```

### Navigate to the Project

```bash
cd portfolio-devops-assignment
```

### Install Dependencies

```bash
npm install
```

### Run the Project

Since the project is a static HTML/CSS/JavaScript application, the website can be opened directly through:

```text
src/index.html
```

Alternatively, it can be served using a local development server.

---

## 🔄 CI/CD Pipeline

GitHub Actions is used to automate the project's development and deployment process.

### Continuous Integration – `ci.yml`

The CI workflow is configured to run when changes are pushed to the main development branches and when pull requests are created.

The pipeline performs:

1. Checkout of the source code
2. Node.js environment setup
3. Dependency installation
4. Linting check
5. Build check
6. Test check

The project currently uses lightweight npm scripts for linting, building, and testing because it is a static HTML/CSS/JavaScript application.

### Continuous Deployment – `deploy.yml`

The deployment workflow is configured to run when changes are pushed to the `main` branch.

The deployment process:

1. Checks out the latest source code.
2. Connects to the configured Vercel project.
3. Uses the configured Vercel credentials/secrets.
4. Deploys the application to the Vercel production environment.

This provides an automated path from the production Git branch to the live application.

---

## ☁️ Deployment

The application is deployed using **Vercel**.

### Deployment Configuration

The repository contains a `vercel.json` configuration file that specifies the project deployment configuration.

The production deployment is connected to the `main` branch through the GitHub Actions deployment workflow.

### Live Application

**Nova Freelance Agency**

https://portfolio-devops-assignment-csg9eo1pp.vercel.app/#contact

---

## 🔀 Git Collaboration Workflow

The team followed a feature-based collaboration process:

```text
                    ┌───────────────┐
                    │     main      │
                    │  Production   │
                    └───────▲───────┘
                            │
                         Merge/PR
                            │
                    ┌───────┴───────┐
                    │    develop    │
                    │  Integration  │
                    └───▲────▲───▲──┘
                        │    │   │
              ┌─────────┘    │   └─────────┐
              │              │             │
      feature/sewwandi  feature/shanika  feature/ahinsa
              │              │             │
          Sewwandi        Shanika        Ahinsa
      ITBIN-2211-0288  ITBIN-2211-0289 ITBIN-2211-0120
```

### Workflow

1. Team members update their local `develop` branch.
2. Each member creates or works on their own feature branch.
3. Features are developed independently.
4. Changes are committed using meaningful commit messages.
5. Feature branches are pushed to GitHub.
6. Pull requests are created for integration.
7. Team members review the changes.
8. Approved changes are merged into the integration branch.
9. The completed project is merged into `main`.
10. Changes to `main` trigger the production deployment workflow.

---

## ⚠️ Challenges & Resolutions

### Deployment Configuration Issues

During development, the team encountered deployment configuration issues where the deployment source and workflow configuration required adjustment.

The deployment configuration was reviewed and updated to ensure that the correct project source was deployed.

### Multiple Deployment Configurations

The project initially contained different deployment workflow configurations while the team tested deployment approaches.

The deployment configuration was refined to support the final Vercel deployment used for the live application.

### Team Collaboration

Because multiple developers worked on different areas of the project, Git branches were used to separate individual work and reduce the risk of directly modifying shared production code.

---

## 📊 Build Status

### Continuous Integration

The project uses GitHub Actions to automatically perform project validation when changes are pushed or pull requests are created.

### Continuous Deployment

The production deployment workflow automatically deploys changes from the `main` branch to Vercel.

**CI Workflow:** `.github/workflows/ci.yml`
**Deployment Workflow:** `.github/workflows/deploy.yml`

---

## 📚 Git Commit & Collaboration Practices

The team followed Git best practices including:

* Feature-based development
* Meaningful commit messages
* Separate branches for individual work
* Pull requests for collaboration
* Code integration through branches
* Maintaining a production-ready `main` branch
* Using GitHub Actions for automation

Examples of conventional commit styles used in the project include:

```text
feat: add homepage functionality
fix: resolve deployment configuration
docs: update README
ci: update CI pipeline
```

---

## 🎯 Assignment Requirements Demonstrated

This project demonstrates the major requirements of the Advanced Git & DevOps assignment:

* ✅ Public GitHub repository
* ✅ Three team members with identified roles
* ✅ Individual feature branches
* ✅ Collaborative Git workflow
* ✅ Multiple commits from team members
* ✅ Pull request based integration
* ✅ GitHub Actions CI workflow
* ✅ Automated deployment workflow
* ✅ Cloud deployment using Vercel
* ✅ Responsive portfolio website
* ✅ Individual contribution documentation
* ✅ Live publicly accessible application

---

## 👥 Team

### Sewwandi Kodippili

**ITBIN-2211-0288**
DevOps Engineer & CI/CD Management

### Shanika Udawaththa

**ITBIN-2211-0289**
Frontend & UI Development

### Ahinsa Abeywickrama

**ITBIN-2211-0120**
JavaScript & Application Logic

---

## 📄 Repository

**GitHub Repository:**
https://github.com/Sewwandi999/portfolio-devops-assignment

**Live Website:**
https://portfolio-devops-assignment-csg9eo1pp.vercel.app/#contact

---

## 🏁 Conclusion

Nova Freelance Agency demonstrates how a small development team can use professional Git and DevOps practices to collaboratively develop, validate, and deploy a web application.

The project combines frontend development with Git branching, collaborative development, GitHub Actions automation, and cloud deployment to demonstrate a complete development-to-deployment workflow.
