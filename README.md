# ChangeLens – AI-Driven Adaptive Software Change Impact Analysis and Intelligent Dependency Management Platform

## Team Members

| S. No. | University ID | Name |
|--------|---------------|------|
| 1 | 2420030400 | Masuma Fathema |
| 2 | 2420030568 | Avinash Yarukala |
| 3 | 2420030287 | Gorantla Divya Sree |

## Supervisor

**Ms. G Lavanya**

## Abstract

**ChangeLens** is an AI-integrated platform designed to analyze the impact of software changes and identify potentially affected components. The system integrates with **GitHub** to detect code changes and analyzes affected modules, dependencies, APIs, and test cases. Using AI, ChangeLens provides impact analysis, risk levels, and recommended actions to help developers make informed decisions before implementing changes. The platform also integrates with **Jira** to create and update development tasks related to identified changes. By continuously adapting its analysis as the software evolves, ChangeLens reduces manual dependency tracking, helps prevent unintended issues, and supports efficient software maintenance.

## Objectives

- Analyze software changes and identify affected components and dependencies.
- Use AI to assess change impact, risks, and recommend appropriate actions.
- Integrate GitHub and Jira to support adaptive software development workflows.
- Reduce manual effort and dependency-related errors during software maintenance.

## Technologies Used

### Frontend
- React.js

### Backend
- Node.js
- Express.js

### Database
- PostgreSQL

### AI
- Gemini API

### APIs & Integration
- GitHub API
- Jira REST API

### DevOps
- GitHub Actions

## Key Features

- **Change Detection** – Detects modifications made to software projects through GitHub.
- **Dependency Analysis** – Identifies modules and components potentially affected by changes.
- **AI Impact Analysis** – Uses AI to analyze changes and explain their possible consequences.
- **Risk Assessment** – Highlights potentially high-risk changes requiring developer attention.
- **Smart Recommendations** – Provides recommended actions based on the detected impact.
- **Jira Integration** – Creates and updates Jira tasks related to identified changes.
- **Adaptive Analysis** – Continuously analyzes new changes as the software project evolves.

## System Workflow

```text
GitHub Repository
        ↓
Change Detection
        ↓
Dependency Analysis
        ↓
AI Impact Analysis
        ↓
Risk Assessment
        ↓
Recommended Actions
        ↓
Jira Task Creation / Update
        ↓
Developer Action
        ↓
Continuous Re-analysis
```

## Setup Instructions

### Prerequisites

Make sure the following software is installed:

- Node.js and npm
- PostgreSQL
- Git
- Docker

### Clone the Repository

```bash
git clone https://github.com/Masuma-86/KLH-CSE-2026-27-2420030400-ChangeLens.git
cd KLH-CSE-2026-27-2420030400-ChangeLens
```

### Install Dependencies

```bash
npm install
```

### Environment Variables

Create a `.env` file in the project directory:

```env
PORT=5000
DATABASE_URL=your_postgresql_connection_string
GEMINI_API_KEY=your_gemini_api_key
GITHUB_TOKEN=your_github_token
JIRA_BASE_URL=your_jira_url
JIRA_EMAIL=your_jira_email
JIRA_API_TOKEN=your_jira_api_token
```

> **Note:** Never upload actual API keys, passwords, or tokens to GitHub.

### Run the Application

```bash
npm run dev
```

The application will start on the local development server.
