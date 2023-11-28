# Flutter-MongoDB-Auth
This is a Flutter project for building a simple authentication app using a Node.js/Express backend with MongoDB for storage.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Contributing](#contributing)
- [License](#license)

## Features

- User registration (signup) and authentication (login) using JWTs.
- Protected endpoint that requires user authentication.
- Flutter frontend for the authentication flow.
- MongoDB for storing user information.
- Dio for making HTTP requests from the Flutter app.

## Getting Started

### Prerequisites

- Flutter SDK (https://flutter.dev/docs/get-started/install)
- Node.js (https://nodejs.org/)
- MongoDB (https://www.mongodb.com/try/download/community)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/GeorgeMichaelOpio/Flutter-MongoDB-Auth.git
   ```

2. Navigate to the server directory:

   ```bash
   cd Flutter-MongoDB-Auth/nodeExpress_API
   ```

3. Install server dependencies:

   ```bash
   npm install
   ```

4. Set up a MongoDB database and update the `.env` file with your MongoDB URI and secret key.

5. Run the server:

   ```bash
   npm start
   ```

6. Navigate to the Flutter app directory:

   ```bash
   cd ../Flutter-MongoDB-Auth/flutter_auth
   ```

7. Run the Flutter app:

   ```bash
   flutter run
   ```

## API Endpoints

- **POST /signup:** Register a new user.
- **POST /login:** Authenticate a user.
- **GET /protected:** Protected endpoint requiring authentication.

## Contributing

Contributions are welcome.

```
