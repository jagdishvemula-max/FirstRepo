# Healthcare Web Application

This project is a healthcare web application that provides functionalities for managing patient data. It consists of a backend built with TypeScript and Express, and a frontend built with React.

## Project Structure

```
healthcare-web-app
├── backend                # Backend application
│   ├── src                # Source files for the backend
│   ├── package.json       # Backend dependencies and scripts
│   └── tsconfig.json      # TypeScript configuration for the backend
├── frontend               # Frontend application
│   ├── src                # Source files for the frontend
│   ├── package.json       # Frontend dependencies and scripts
│   └── tsconfig.json      # TypeScript configuration for the frontend
├── .env.example           # Example environment variables
├── docker-compose.yml     # Docker configuration for the application
├── package.json           # Overall project dependencies and scripts
└── tsconfig.json          # Overall TypeScript configuration
```

## Features

- **Patient Management**: Create, read, update, and delete patient records.
- **Responsive UI**: A user-friendly interface built with React.
- **API Integration**: Communicates with the backend to manage patient data.

## Getting Started

### Prerequisites

- Node.js
- Docker (for containerized deployment)

### Installation

1. Clone the repository:
   ```
   git clone <repository-url>
   cd healthcare-web-app
   ```

2. Install backend dependencies:
   ```
   cd backend
   npm install
   ```

3. Install frontend dependencies:
   ```
   cd frontend
   npm install
   ```

### Running the Application

To run the application, you can use Docker Compose:

```
docker-compose up
```

This will start both the backend and frontend services.

### Environment Variables

Copy the `.env.example` file to `.env` and update the values as needed.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License.