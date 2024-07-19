# Cricket Score Tracker

Welcome to the Cricket Score Tracker, a comprehensive application that provides real-time cricket match scores and other related information. This project combines a robust Spring Boot backend with an interactive Angular frontend to deliver an engaging user experience for cricket enthusiasts.

## Overview

**Cricket Score Tracker** consists of two main components:

1. **Spring Boot Backend**
   - Provides RESTful APIs to fetch live cricket scores, point tables for major tournaments like CWC 2023, and a list of all matches.
   - Utilizes the `CricketService` to interact with data sources and deliver accurate and up-to-date information.

2. **Angular Frontend**
   - Displays live scores and match details through an intuitive and user-friendly interface.
   - Implements components such as `LiveMatchCardComponent` and integrates `NgxTypedJsModule` for dynamic UI effects.
   - Provides features to refresh scores and handle loading states effectively.

## Features

- **Live Match Scores:** Get real-time updates on ongoing cricket matches.
- **Tournament Point Tables:** View the latest standings for CWC 2023 and other major tournaments.
- **Interactive UI:** Enjoy a responsive and interactive experience with dynamic score updates.
- **Error Handling:** Gracefully manages API errors and loading states.

## Getting Started

### Prerequisites

- **Java 11** or later for running the Spring Boot application.
- **Node.js** and **npm** for running the Angular application.

### Backend Setup

1. Clone the repository:

    ```bash
    git clone <repository-url>
    cd cricket-score-tracker/backend
    ```

2. Install dependencies and run the Spring Boot application:

    ```bash
    ./mvnw clean install
    ./mvnw spring-boot:run
    ```

3. The backend will be available at `http://localhost:8080`.

### Frontend Setup

1. Navigate to the frontend directory:

    ```bash
    cd cricket-score-tracker/frontend
    ```

2. Install dependencies and start the Angular application:

    ```bash
    npm install
    ng serve
    ```

3. The frontend will be available at `http://localhost:4200`.

## API Endpoints

- **GET /cricket/live:** Fetch live match scores.
- **GET /cricket/point-table:** Retrieve the CWC 2023 point table.
- **GET /cricket:** Get a list of all matches.

## Contributing

Feel free to submit issues, pull requests, or suggestions to improve the project. Contributions are always welcome!

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Enjoy using the Cricket Score Tracker! For any questions or feedback, please contact us at [support@cricketscoretracker.com](mailto:support@cricketscoretracker.com).
