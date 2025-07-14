Alien Defense Game + Wallet Connect (Testnet Demo)

This is a demo project for the *Honeycomb Protocol Game Jam*, combining an on-chain mission system with a basic spaceship shooter game.

How It Works

1. *Wallet Connect Page*  
Users first land on a simple wallet connect page where they connect their Backpack wallet on testnet.  
After connection, their wallet address is stored in the browser (localStorage), and they're redirected to the game.

2. *Game Page*  
The game starts with a mission objective (e.g. survive 5 minutes or kill 100 aliens).  
Progress is recorded off-chain for now, but the setup simulates how missions and on-chain logic could tie into gameplay.

Technologies Used

- Vanilla JavaScript  
- HTML/CSS  
- Wallet Connect (testnet, e.g. Backpack)  
- LocalStorage for wallet persistence  
- Hosted on a custom domain
