# UdaciRacer Simulation Game 🚗💨

## 📌 Overview

Welcome to **UdaciRacer**, an interactive and fast-paced racing simulation game! This game allows players to select a racer and track, start the race, and accelerate their car in real time while competing against AI-driven opponents. The game features a live leaderboard, dynamic race mechanics, and a final results screen displaying player rankings.

## 🎮 Features

- **Race Selection:** Choose from multiple cars and tracks.
- **Real-time Racing:** Compete against AI-driven racers.
- **Acceleration Mechanics:** Click to boost speed and gain an advantage.
- **Live Leaderboard:** Stay updated on racer positions throughout the race.
- **Final Results:** View your placement after the race.
- **Fully Asynchronous Gameplay:** Smooth API integration for seamless user experience.

## 🚀 Getting Started

### 🔧 Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/YourUsername/UdaciRacer.git
   cd UdaciRacer
   ```
2. **Install Dependencies**
   ```bash
   npm install
   ```

### 🏁 Running the Game

#### **1️⃣ Start the Backend Server**

The game logic is handled by a Go-based API. Follow these steps to start the server:

```bash
cd api
go build
./api
```

The server will run on `http://localhost:3001`.

#### **2️⃣ Start the Frontend**

In the project root directory, run:

```bash
npm start
```

Once the frontend starts, access the game at `http://localhost:3002`.

## 🔗 API Endpoints

| Method | Endpoint               | Description |
|--------|------------------------|-------------|
| GET    | `/api/tracks`          | Retrieve available tracks |
| GET    | `/api/cars`            | Retrieve available cars |
| GET    | `/api/races/:id`       | Get race details |
| POST   | `/api/races`           | Create a new race |
| POST   | `/api/races/:id/start` | Start the race |
| POST   | `/api/races/:id/accelerate` | Boost player's speed |

## 🛠️ Project Structure

```
UdaciRacer/
│── api/                # Backend API (Go server)
│── src/
│   ├── client/
│   │   ├── assets/
│   │   │   ├── css/  # Styling files
│   │   │   ├── images/
│   │   │   ├── javascript/
│   │   │   │   ├── index.js  # Main game logic
│   │   │   │   ├── api.js    # API calls
│   │   ├── index.html  # Game UI
│── package.json  # Project dependencies
│── README.md  # Project documentation
```

## 📖 How the Game Works

1. **Select a Racer & Track** – Choose from a list of cars and tracks.
2. **Start the Race** – The race begins when you hit the start button.
3. **Accelerate** – Click to boost your car's speed and improve your position.
4. **Monitor the Leaderboard** – Watch as positions change dynamically.
5. **View Results** – See the final rankings once the race ends.

## 🏆 Challenges & Enhancements

✔️ **Implemented dynamic API calls for real-time updates.**
✔️ **Optimized leaderboard updates for smoother performance.**
✔️ **Enhanced UI/UX for a more engaging gameplay experience.**
✔️ **Improved error handling and API request efficiency.**
✔️ **Refactored code for better readability and maintainability.**

## 🎯 Future Improvements

🔹 Implement multiplayer support.
🔹 Add sound effects and animations for a more immersive experience.
🔹 Introduce difficulty levels and AI enhancements.

## 🤝 Contributing

Contributions are welcome! Feel free to submit issues or pull requests.

## 📜 License

This project is licensed under the MIT License.

## 🙌 Acknowledgments

Special thanks to Udacity for providing the foundational materials for this project.

---

🚀 **Enjoy Racing! May the fastest racer win!** 🏎️💨

