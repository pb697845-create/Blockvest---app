# BlockVest - Digital Asset Management

A modern React application for managing digital assets with confidence.

## Features
- 📊 **Portfolio Dashboard**
- Real-time performance tracking with advanced analytics
- 🔒 **Secure Custody**
- Multi-layer encryption, cold storage, and 2FA
- 📈 **Smart Analytics**
- Market trends, risk scoring, and portfolio optimization

## Project Structure
blockvest-app/
├── public/
│   └── index.html
├── src/
│   ├── components/
│   │   ├── Header.jsx
│   │   ├── Header.css
│   │   ├── Hero.jsx
│   │   ├── Hero.css
│   │   ├── Features.jsx
│   │   ├── Features.css
│   │   ├── Dashboard.jsx
│   │   ├── Dashboard.css
│   │   ├── Footer.jsx
│   │   └── Footer.css
│   ├── App.js
│   ├── App.css
│   ├── index.js
│   └── index.css
├── .env
├── .gitignore
├── package.json
└── README.md

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/pb697845-create/Blockvest---app.git
   cd Blockvest---app
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm start
   ```
   The app will open at http://localhost:3000

## Available Scripts
- `npm start` - Runs the app in development mode
- `npm build` - Builds the app for production
- `npm test` - Runs the test suite
- `npm eject` - Ejects from create-react-app (irreversible)

## Customization

### Update Colors
Edit the color variables in component CSS files:
- Primary green: #00C896
- Dark background: #0E1A2B
- Card background: #111F33

### Add New Sections
1. Create a new component in `src/components/`
2. Import and add it to `src/App.js`
3. Style with a corresponding CSS file

## Future Enhancements
- User authentication
- Real-time price data integration
- Portfolio management features
- Trading functionality
- Mobile app
- Dark/Light theme toggle
- API integration

## License
MIT License - See LICENSE file for details

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.