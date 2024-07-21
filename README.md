# Zelda Cookbook

This application provides an easy-to-use interface for users to discover recipes and their required ingredients. The app features a PostgreSQL database for storing recipes and ingredients, a Node.js backend API server, and a Node.js frontend UI server.
![Zelda Cookbook Screenshot](./zelda-cookbook-frontend//LoZ-cookbook.png)

## Features

- **Recipe Database**: PostgreSQL database containing recipes and ingredients.
- **Backend API**: Node.js server that provides endpoints to interact with the recipe database.
- **Frontend UI**: Node.js server that displays the recipes and ingredients in a user-friendly interface.

### Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Dvora-K/Zelda-Cookbook.git
   cd Zelda-Cookbook
   ```

2. **Build and Run the Containers**
   ```bash
   docker-compose up --build
   ```

3. **Access the Application**
   - **Backend API**: `http://localhost:3000/api/v1/ingredients`
   - **Frontend UI**: `http://localhost:3010`

## Technologies Used

- **PostgreSQL**: Version 12.18
- **Node.js**: Versions 12 and 8
- **Docker**: For containerizing the application
- **Docker Compose**: For managing multiple containers