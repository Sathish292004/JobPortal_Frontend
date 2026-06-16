# Job Portal Frontend

A simple React-based Job Portal application that displays job listings fetched from a REST API.

## Features

- View available job postings
- Display:
  - Job Profile
  - Job Description
  - Required Experience
  - Technology Stack
- Responsive UI using Material UI
- API integration using Axios

## Tech Stack

- React 18
- Material UI (MUI)
- Axios
- JSON Server (Mock Backend)

## Project Structure

```text
src/
├── components/
│   └── Search.jsx
├── App.js
└── index.js
```

## Installation

### Clone Repository

```bash
git clone https://github.com/Sathish292004/JobPortal_Frontend.git
cd JobPortal_Frontend-main
```

### Install Dependencies

```bash
npm install
```

## Running Mock Backend

Install JSON Server globally:

```bash
npm install -g json-server
```

Start server:

```bash
json-server --watch db.json --port 3001
```

API Endpoint:

```text
http://localhost:3001/posts
```

## Running Frontend

```bash
npm start
```

Application runs at:

```text
http://localhost:3000
```


## Future Enhancements

- Search jobs by skill
- Filter by experience
- Job details page
- Apply for jobs
- Authentication
- Backend integration with Spring Boot
- Pagination and sorting

## Author

Job Portal Frontend Project built using React and Material UI.
