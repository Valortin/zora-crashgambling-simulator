# 🚀 Zora Coin Crash Gambling Simulator  
**Supercharge Zora Coins with AI-Powered Volatility Gaming**  
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) 
[![Zora SDK](https://img.shields.io/badge/Powered%20by-Zora%20SDK-000000.svg)](https://docs.zora.co/coins)  

## 🌟 Overview  

A high-octane gambling experience where Zora Coins (ERC-20 tokens) meet AI-driven crash mechanics. Players bet on a rising multiplier curve, cashing out before it crashes—all while generating referral fees for creators and traders via Zora’s Coins Protocol. Built for **Zora’s 2nd Wave Hackathon**. 

A recreation of the popular online casino game "crash" with accurate casino odds. 

![showcase](https://i.imgur.com/bpXV3zI.png)

## 🎮 Features  
- **🪙 Zora Coin Bets**: Use any Zora Coin (e.g., $MEME2023, $AIART) as in-game currency.  
- **🤖 AI Crash Prediction**: ML model adjusts odds using historical data and social sentiment.  
- 💸 **Real-Time Payouts**: Instant withdrawals powered by Zora’s SDK and Base L2.  
- 🏆 **Multiplayer Leaderboards**: Compete globally with Socket.io-powered live races.  
- 📢 **Social Integration**: Share bets on Farcaster and clone influencer strategies.  

## Technologies Used 

* [React.js](https://reactjs.org/) - JS framework used to create the frontend.
*  [Express.js](https://expressjs.com/) - The backend server environment and serves as an API.
* [Node.js](https://nodejs.org/en/) - JS environment that executes JS outside of the browser.
* [Socket.io](https://socket.io/) - Allows communication between the server and client in real time. 
* [MongoDB](https://www.mongodb.com/) - NoSQL database used to store all user and server information. 
* [Passport.js](https://www.passportjs.org/) - Middleware used to authenticate and authorize users. Handles logins and registrations.
* [bcrypt.js](https://www.npmjs.com/package/bcrypt) - Secures user passwords by hashing all passwords before storing in database. 
* [Chart.js](https://www.chartjs.org/) - Create visualizations of data through charts and graphs like line graphs. 
* HTML
* CSS

## Features
* Login system - Users must log in or create an account to place bets. 
* Betting system - Users wager their balance before the round begins. A multiplier counts up from 1.00 and users can cash out at any time, multiplying their bet amount by the current multiplier. The multiplier will stop, or crash, at a randomly generated value, and users who have not cashed out yet will lose their entire bet. 
* Accurate Gambling Odds - Every crash value is generated using the same algorithms real casinos use, including a 3% house edge. 
* Live Bet Tracker - Users can see other users betting live. When a user places a bet, their username and bet amount are added to a live table. When the user cashes out, their cash out multiplier and profit are also added. 
* Game History - Displays the crash values of the last 25 games played along with the streak of games with crash values above or below 2.00. 
* Chat - Users who are logged in can send messages to other users through chat 
* Live Line Graph - Visualization of the current multiplier with respect to time. 

## Installation 
    // Clone the repository
    $ git clone https://github.com/Valortin/zora-crashgambling-simulator
    
    // Navigate to directory
    $ cd ./Online-Crash-Gambling-Simulator

### Setup and Run Client

    // Navigate to client directory 
    $ cd ./client
    
    // install packages
    $ npm i 
    
    // start client (localhost:3000)
    $ npm start
    
    // For running in production
    $ npm run build
    $ npm start

### Setup and Run Server

    // Navigate to server directory 
    $ cd ./backend
    
    // install packages
    $ npm i 
    
    // install nodemon for development
    $ npm i -D nodemon
    
    // start node server (localhost:4000) and socket.io server (localhost:3001) 
    $ npm start 

### Environment Variables 
* MONGOOSE_DB_LINK - URL to MongoDB server 
* PASSPORT_SECRET -  Secret for Passport.js authorization and authentication 
