# React Todo App

This repository contains the source code for a simple yet powerful to-do application built with React. It is designed to demonstrate basic React concepts, state management, and best practices in application structure.

## Features

- Add, delete, and mark tasks as completed.
- Filter tasks based on their completion status.
- Clean and responsive user interface.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Before running this project, you need to have Node.js and npm (Node Package Manager) installed on your system.

- Node.js
- npm

### Installing

1. Clone the repo:
```
git clone https://github.com/gurjitsingh445456t/todo.git
```

2. Navigate to the project directory:
```
cd todo
```

3. Install dependencies:
```
npm install
```

4. Start the development server:
```
npm start
```

The application will open in your default browser at `http://localhost:3000`.

## CI/CD Pipeline

Our project uses a robust CI/CD pipeline to ensure consistent quality and seamless deployment. The pipeline is set up to run tests and generate a coverage report using Jest upon every commit.

### Continuous Integration

- **Automated Testing:** Every pull request triggers an automated test suite in our CI environment. This ensures that all new changes meet the quality standards without breaking existing functionalities.
- **Coverage Report:** Jest is used to generate a test coverage report. This helps us maintain high-quality code with good test coverage.

### Continuous Deployment

- **Automatic Deployment:** Upon successful integration, changes are automatically deployed to the staging environment, ensuring a continuous delivery process.
- **Production Deployment:** After thorough testing in the staging environment, changes are manually promoted to production.

## Running Tests

To ensure the quality and correctness of the application, we have included a suite of tests.

- To run the tests, execute:
```
npm t
```

### Test Coverage

Understanding the extent of test coverage is crucial in maintaining a reliable application.

- To check the test coverage report, run:
```
npm t -- --coverage
```

- To view the coverage report in the browser, after running the above command, type:
```
open coverage/lcov-report/index.html
```

## Built With

- [React](https://reactjs.org/) - A JavaScript library for building user interfaces
- [Create React App](https://create-react-app.dev/) - An officially supported way to create single-page React applications

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/gurjitsingh445456t/todo/tags).

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
