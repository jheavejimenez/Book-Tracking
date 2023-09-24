# Contributing Guidelines

Welcome to the development of Book Tracking We appreciate your interest in contributing to our project.
To ensure a smooth and productive collaboration, please follow these guidelines.

## Getting Started

1. **Fork the Repository**: Start by forking the repository to your GitHub account.

2. **Clone the Repository**: Clone your forked repository to your local development environment.

```bash
git clone https://github.com/yourusername/your-monolithic-app.git
```

3. **Install Dependencies**: Make sure you have Node.js and Python (for FastAPI) installed on your system. Then, 
install the project dependencies for both the frontend and backend:

```bash
# Frontend (Next.js)
cd frontend
npm install

# Backend (FastAPI)
cd ../backend
pip install -r requirements.txt
```

## Using Docker 

- The project is Dockerized for easy deployment. The `Dockerfile` and `docker-compose.yml` files are available in the project root.

- To build and run the Docker containers, use the following commands:

```bash
docker-compose up --build
```

- Access the frontend at `http://localhost:3000` and the backend at `http://localhost:8000` in your web browser.

## Development Workflow

1. **Create a New Branch**: Before making any changes, create a new branch for your feature or bug fix.
Please use a descriptive branch name, such as `feature/new-feature` or `bugfix/issue-123`.

```bash
git checkout -b feature/new-feature
```

2. **Coding Standards**: Adhere to the coding standards and style guidelines for both the frontend and backend code.
Consistent code formatting makes it easier for everyone to collaborate.

3. **Testing**: Write tests for new features or bug fixes. Ensure that all tests pass before submitting your changes.

4. **Commit Messages**: Write clear and concise commit messages. Use the [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) format if possible.

5. **Pull Request**: When your feature or bug fix is ready, open a pull request (PR) to the `main` branch of the original repository.
Provide a detailed description of the changes made in the PR.

6. **Review Process**: Your PR will be reviewed by maintainers and other contributors. Be prepared to make changes based on feedback.

## Documentation

- Keep the project documentation up to date. This includes updating [README ](./README.md) files, code comments, and API documentation (if applicable).

## Issues and Bug Reports

- If you encounter any issues or want to report a bug, please create a new issue in the GitHub repository. 
Include detailed information about the problem, steps to reproduce it, and your environment.


Thank you for your contribution! Your efforts are valuable in making Book Tracking even better.
