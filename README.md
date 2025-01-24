# Bicycle Repair Online System

Welcome to the Bicycle Repair Online System! This application facilitates the triage and quoting of bicycle repairs, communication between repair technicians and customers, and the scheduling of bicycle pickup and delivery.

## Features

- **DIY Support from a GPT Enabled "Hipster Bike Mechanic AI" chatbot named Lloyd
- **Triage and Quoting**: Easily log repair requests and generate quotes for customers.
- **Communication**: Streamline communication between repair technicians and customers through the platform.
- **Scheduling**: Schedule the pickup and delivery of bicycles for repair, ensuring a smooth and efficient process.

## Getting Started

### Prerequisites

Before you begin, ensure you have met the following requirements:

- You have installed the latest version of [Node.js](https://nodejs.org/).
- You have a [MongoDB](https://www.mongodb.com/) database set up for data storage.

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/bicycle-repair-system.git
    ```
2. Navigate to the project directory:
    ```bash
    cd bicycle-repair-system
    ```
3. Install the dependencies:
    ```bash
    npm install
    ```

### Configuration

1. Create a `.env` file in the root directory and add the following environment variables:
    ```env
    DB_URI=<your-mongodb-uri>
    PORT=<your-preferred-port>
    ```

### Usage

1. Start the application:
    ```bash
    npm start
    ```
2. Open your browser and navigate to `http://localhost:<your-preferred-port>` to access the system.

## Contributing

To contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch:
    ```bash
    git checkout -b feature/your-feature-name
    ```
3. Make your changes and commit them:
    ```bash
    git commit -m 'Add some feature'
    ```
4. Push to the branch:
    ```bash
    git push origin feature/your-feature-name
    ```
5. Create a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to the [Node.js](https://nodejs.org/) and [MongoDB](https://www.mongodb.com/) communities for their excellent resources and support.
