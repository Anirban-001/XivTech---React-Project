***Real-Time Crypto Tracker***
This project is a real-time cryptocurrency tracker that displays live information about various cryptocurrencies, including their prices, 24h changes, market cap, and volume. The app features a responsive design, theme toggling (dark/light mode), and an interactive table that allows users to sort the data by different criteria.

Features
Real-time Data: Displays live data for popular cryptocurrencies.

Sorting: Sort coins by price or 24-hour price change.

Dark/Light Mode: Toggle between light and dark modes for the app.

Responsive Design: The layout adapts to different screen sizes for a seamless experience across devices.

Top Gainers: Displays the cryptocurrency with the highest 24h change.

Tech Stack
Frontend: React.js

State Management: Redux (for managing the state)

Styling: CSS (for responsive design and theme toggling)

API (Simulated): Data simulation for cryptocurrency prices (as no live API is integrated).

Installation
Prerequisites
Make sure you have the following installed:

Node.js (LTS version)

npm or yarn

Steps to Run the Project Locally
Clone the repository:

bash
Copy
Edit
git clone https://github.com/Anirban-001/XicTech---React-Project.git
cd crypto-tracker
Install dependencies: If you’re using npm:

bash
Copy
Edit
npm install
If you’re using yarn:

bash
Copy
Edit
yarn install
Start the development server: If you’re using npm:

bash
Copy
Edit
npm start
If you’re using yarn:

bash
Copy
Edit
yarn start
Visit the app in your browser at http://localhost:3000.

Project Structure
graphql
Copy
Edit
crypto-tracker/
├── public/
│   ├── index.html         # HTML file where the React app is rendered
│   ├── assets/            # Images, icons, and other static assets
├── src/
│   ├── components/        # React components (e.g., CryptoTable, ThemeToggle)
│   ├── utils/             # Utility functions (e.g., simulated data)
│   ├── App.jsx            # Main React component
│   ├── App.css            # Styles for the app
│   ├── index.js           # React entry point
│   ├── sampleData.js      # Dummy cryptocurrency data for the app
├── package.json           # Project metadata and dependencies
└── README.md              # This README file
Components
1. CryptoTable
The CryptoTable component displays the list of cryptocurrencies. It includes a table with the following columns:

Coin Logo

Coin Name

Price

24h Change

Market Cap

Volume in 24h

2. ThemeToggle
The ThemeToggle component allows the user to switch between dark mode and light mode.

3. App
The main component that holds the state and renders the CryptoTable and ThemeToggle components.

Styling
The app uses custom CSS to style the components. The design is responsive, with special styles for dark and light modes.

Contributing
We welcome contributions! If you’d like to improve the app, feel free to fork the repository and submit a pull request. Here's how you can contribute:

Fork the repository.

Create a new branch for your feature or bugfix.

Make your changes.

Write tests if necessary.

Submit a pull request.

License
This project is licensed under the MIT License - see the LICENSE file for details.
