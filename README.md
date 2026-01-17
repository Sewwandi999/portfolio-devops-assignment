# Nova Freelance Agency – DevOps Portfolio Website

## Group Information

* **Student 1:** Sewwandi Kodippili Sewwandi K.S – ITBIN-2211-0288 – Role: DevOps Engineer & CI/CD Management
* **Student 2:** Shanika Udawaththa U.A.D.N – ITBIN-2211-0289 – Role: Frontend & UI Development
* **Student 3:** Ahinsa Abeywickrama A.N – ITBIN-2211-0120 – Role: JavaScript & Application Logic

---

## Project Description

This project is a static portfolio website developed for a DevOps and GitHub assignment.
The website represents a freelance digital agency and showcases services, skills, projects, and contact information.
The main focus of the project is implementing **proper Git workflow, branching strategy, CI/CD pipelines, and automated deployment** using GitHub Actions.

---

## Live Deployment

🔗 **Live URL:**
https://sewwandi999.github.io/portfolio-devops-assignment/

---

## Technologies Used

* HTML5
* CSS3
* JavaScript
* Git & GitHub
* GitHub Actions (CI/CD)
* GitHub Pages (Deployment Platform)

---

## Features

* Responsive and modern UI design
* Services and skills showcase section
* Contact form with JavaScript interaction
* Automated CI pipeline on push and pull requests
* Automated deployment to GitHub Pages

---

## Branch Strategy

We implemented the following branching strategy:

* `feature/sewwandi` – ITBIN-2211-0288
* `feature/shanika` – ITBIN-2211-0289
* `feature/ahinsa` – ITBIN-2211-0120

---

## Individual Contributions

### Sewwandi Kodippili (ITBIN-2211-0288)

* Repository setup and configuration
* Branch strategy implementation
* GitHub Actions CI pipeline configuration
* GitHub Pages deployment pipeline setup
* Managed secrets, workflows, and deployment fixes

### Shanika Udawaththa (ITBIN-2211-0289)

* Website layout and responsive UI design
* HTML structure and CSS styling
* Services, projects, and portfolio sections
* UI improvements and visual consistency

### Ahinsa Abeywickrama (ITBIN-2211-0120)

* JavaScript functionality implementation
* Contact form interaction logic
* Client-side behavior handling
* Code cleanup and validation

---

## Setup Instructions

### Prerequisites

* Git
* Web browser (Chrome, Edge, Firefox)

### Installation

```bash
# Clone the repository
git clone https://github.com/sewwandi999/portfolio-devops-assignment.git

# Navigate to project directory
cd portfolio-devops-assignment
```

No additional dependencies are required since this is a static website.

---

## Deployment Process

The project uses **GitHub Actions** for CI/CD:

1. **CI Pipeline (`ci.yml`)**

   * Triggered on push and pull requests
   * Performs basic validation checks for HTML, CSS, and JavaScript files

2. **Deployment Pipeline (`deploy.yml`)**

   * Triggered on push to the `main` branch
   * Uploads the static site artifacts
   * Automatically deploys the site to **GitHub Pages**

Once the workflow completes successfully, the live site is updated automatically.

---

## Challenges Faced

* Initial deployment showed README.md instead of the website due to incorrect publish directory.
* This was resolved by configuring the GitHub Pages workflow to deploy from the correct source folder.
* Removing Vercel deployment and migrating fully to GitHub Pages required workflow refactoring.

---

## Build Status

CI/CD is handled using GitHub Actions.
All commits to the `main` branch trigger automated deployment.

---
