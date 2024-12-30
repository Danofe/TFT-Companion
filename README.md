# TFT Companion

A dynamic and interactive overlay for **Teamfight Tactics (TFT)** that helps players with the best builds, champion recommendations, and item setups. Designed to work as both an **in-game overlay** and a **standalone app**, this project ensures you stay ahead of the competition, all coded in React Native.

## Features

### Overlay Features
- **Dynamic Builds**: Automatically updates to reflect the latest TFT patch using the Riot Games API.
- **Champion Recommendations**: Displays optimal champions and team compositions.
- **Item Suggestions**: Recommends the best items for each champion based on the current meta.
- **In-Game Integration**: Functions as an overlay within TFT to provide real-time assistance during matches.

### Standalone Features
- **Build Explorer**: Browse meta builds, champions, and item guides outside the game.
- **Search Functionality**: Quickly find strategies and recommendations.
- **Patch Notes Integration**: Highlights key changes and their impact on the meta.

## Technologies Used
- **React Native**: For building cross-platform mobile applications.
- **Riot Games API**: To fetch real-time data about TFT builds, items, and patches.
- **Overlay Framework**: For in-game integration (e.g., Overwolf or similar solutions).
- **NativeWind**: Tailwind CSS for styling in React Native.

## Getting Started

### Prerequisites
- **Node.js**: Ensure you have Node.js installed.
- **React Native Environment**: Set up React Native development tools as per the [official guide](https://reactnative.dev/docs/environment-setup).
- **Riot API Key**: Obtain a developer key from the [Riot Games Developer Portal](https://developer.riotgames.com/).

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/tft-companion-overlay.git
   cd tft-companion-overlay
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Add your Riot API key to the environment variables:
   - Create a `.env` file in the root directory.
   - Add the following:
     ```env
     RIOT_API_KEY=your_api_key_here
     ```
4. Start the development server:
   ```bash
   npm start
   ```

## Usage

### Overlay Mode
1. Launch the TFT Companion Overlay.
2. Activate the in-game overlay using the integrated framework.
3. Enjoy real-time build and item suggestions while playing TFT.

### Standalone Mode
1. Open the app on your device.
2. Explore builds, champions, and items without needing to launch TFT.

## Contributing
Contributions are welcome! To get started:
1. Fork the repository.
2. Create a new branch for your feature/bugfix.
3. Submit a pull request with detailed information about your changes.

