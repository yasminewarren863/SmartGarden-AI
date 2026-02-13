# SmartGarden AI

[![GitHub issues](https://img.shields.io/github/issues/yasminewarren863/SmartGarden-AI)](https://github.com/yasminewarren863/SmartGarden-AI/issues)  
[![GitHub stars](https://img.shields.io/github/stars/yasminewarren863/SmartGarden-AI)](https://github.com/yasminewarren863/SmartGarden-AI/stargazers)

---

## Overview

SmartGarden AI is a cutting-edge application designed to help gardeners of all levels maintain healthy and thriving plants. By leveraging artificial intelligence and IoT sensor data, it provides real-time insights and personalized care recommendations tailored to your garden’s unique environment.

---

## Features

- Real-time soil moisture and temperature monitoring
- Automated watering schedule recommendations
- AI-driven pest and disease detection from plant images
- Customizable plant database with care instructions
- Push notifications and alerts for plant care

---

## Tech Stack

- Frontend: React.js with Material-UI
- Backend: Node.js, Express
- AI: TensorFlow.js for image recognition
- Database: MongoDB Atlas
- IoT Integration: MQTT protocol for sensor data ingestion

---

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yasminewarren863/SmartGarden-AI.git
   cd SmartGarden-AI
   ```

2. Install dependencies for backend and frontend:

   ```bash
   cd backend && npm install
   cd ../frontend && npm install
   ```

3. Configure environment variables for backend (create `.env` file):

   ```
   MONGODB_URI=<your_mongodb_connection_string>
   MQTT_BROKER=<your_mqtt_broker_url>
   PORT=5000
   ```

4. Start backend server:

   ```bash
   cd backend
   npm start
   ```

5. Start frontend app:

   ```bash
   cd ../frontend
   npm start
   ```

---

## Usage

- Access the web app at `http://localhost:3000`
- Add your plants to the database and connect your garden sensors
- Upload pictures of your plants for AI analysis
- Receive tailored care tips and alerts to keep your garden flourishing

---

## Screenshots

> ![Dashboard Mockup](https://via.placeholder.com/800x400?text=Dashboard+Screenshot+Placeholder)
> 
> ![Plant Detail View](https://via.placeholder.com/800x400?text=Plant+Detail+View+Screenshot+Placeholder)

---

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repo on GitHub: https://github.com/yasminewarren863/SmartGarden-AI/fork
2. Clone your fork:

   ```bash
   git clone https://github.com/yasminewarren863/SmartGarden-AI.git
   ```

3. Create a new branch for your feature:

   ```bash
   git checkout -b feature/YourFeatureName
   ```

4. Make your changes and commit with descriptive messages.
5. Push your branch and open a pull request.

Please ensure all new code is covered by tests and follows the project's code style.

---

## License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/yasminewarren863/SmartGarden-AI/blob/main/LICENSE) file for details.

---

## Author

[![Profile](https://avatars.githubusercontent.com/u/50216189?v=4&s=50)](https://github.com/yasminewarren863)  
**Yasmine Warren** – [GitHub](https://github.com/yasminewarren863) | [Portfolio](https://yasminewarren863.github.io)  

---

*Thank you for using SmartGarden AI! Let's grow smart together.*
