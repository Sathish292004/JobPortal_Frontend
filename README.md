# 💻 Job Portal Frontend

A responsive React-based Job Portal frontend that lets users browse job listings through a clean Material UI interface, with seamless API integration via Axios.

## Overview

This is the client-side application for the Job Portal project. It fetches job postings from a REST API and displays them in a clean, responsive UI. It's designed to pair with the [JobPortal_Backend](https://github.com/Sathish292004/JobPortal_Backend) Spring Boot API, but ships with a mock backend (JSON Server) so you can run it standalone.

## Features

- View available job postings
- Displays for each posting:
  - Job Profile
  - Job Description
  - Required Experience
  - Technology Stack
- Responsive UI built with Material UI
- API integration using Axios

## Tech Stack

| Layer | Technology |
|---|---|
| Framework | React 18 |
| UI Library | Material UI (MUI) |
| HTTP Client | Axios |
| Mock Backend | JSON Server |

## Project Structure

```
src/
├── components/
│   └── Search.jsx
├── App.js
└── index.js
```

## Getting Started

### Prerequisites

- Node.js and npm installed

### Clone & Install

```bash
git clone https://github.com/Sathish292004/JobPortal_Frontend.git
cd JobPortal_Frontend
npm install
```

### Run with the Mock Backend

This project ships with a `db.json` file you can serve locally using JSON Server.

```bash
# Install JSON Server globally (one-time)
npm install -g json-server

# Start the mock API
json-server --watch db.json --port 3001
```

Mock API available at:

```
http://localhost:3001/posts
```

### Run with the Real Backend

To connect to the actual [JobPortal_Backend](https://github.com/Sathish292004/JobPortal_Backend) Spring Boot API instead, update the API base URL in the project (wherever Axios calls are made) to:

```
http://localhost:8080/jobPosts
```

> Make sure the backend is running first — see its README for setup instructions.

### Run the Frontend

```bash
npm start
```

The app will be available at:

```
http://localhost:3000
```

## Roadmap

- [ ] Search jobs by skill
- [ ] Filter by experience
- [ ] Job details page
- [ ] Apply for jobs
- [ ] Authentication
- [ ] Full backend integration with Spring Boot (replacing the mock JSON Server)
- [ ] Pagination and sorting

## Related Projects

- ⚙️ [JobPortal_Backend](https://github.com/Sathish292004/JobPortal_Backend) — Spring Boot REST API powering this app

## Author

**Sathish Kumar B**
GitHub: [@Sathish292004](https://github.com/Sathish292004)

---

⭐ If you found this project useful, consider giving it a star!
