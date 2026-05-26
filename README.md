# Task Tracker API

A simple REST API for managing tasks. Built with Node.js and Express.

## Fetures

- Create, read, update, and delete tasks
- Filter tasks by status (active, completed)
- RESTful API design

## Getting Started

### Prerequisites

- Node.js 18+
- npm or bun

### Instalation

```bash
git clone https://github.com/ayyazzafar/fork-demo-repo.git
cd fork-demo-repo
npm install
```

### Running the Server

```bash
npm start
```

The server will start on `http://localhost:3000`.

## API Endpoints

| Method | Endpoint | Descrption |
|--------|----------|------------|
| GET | /tasks | Get all tasks |
| POST | /tasks | Create a new task |
| PUT | /tasks/:id | Update a task |
| DELETE | /tasks/:id | Delete a task |

## Contibuting

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

## License

MIT
