

<h1>Chess.Game Clone</h1>

A real-time multiplayer chess game inspired by chess.com, built with Node.js, React, Express, and Socket.io for server communication. The game allows two players to connect from the same device and play against each other turn by turn (as Black and White).

![Screenshot 2024-08-26 235706](https://github.com/user-attachments/assets/b4811e28-8709-47c1-91b8-2e5e6679632e)


<h1>Features</h1>
<ul>
  <li><b>Real-Time Multiplayer</b>: Players can connect from the same device using different browser windows and play against each other in real time.</li>
<li><b>Turn-Based Gameplay</b>: The game follows standard chess rules, with players taking turns to make their moves.</li>
<li>Socket.io Integration</b>: Real-time communication between the players is handled using Socket.io.</li><b>
</ul>

<h1>Technologies Used</h1>
<ul>
  <li>Frontend: React.js, Tailwind CSS</li>
  <li>Backend: Node.js, Express.js</li>
  <li>Real-Time Communication: Socket.io</li>
</ul>

<h1>Installation</h1>
<b>Clone the repository:</b>
<ul>
  <li>git clone https://github.com/your-username/chess-game-clone.git</li>
  <li>cd chess-game-clone</li>
  <li>Install the required Node modules using npm install</li>
  <li>Start the server using nodemon (Make sure nodemon is installed globally):
npx nodemon</li>
  <li>Open the game in your browser by navigating to:http://localhost:3000</li>
</ul>

<b>
To play with two players on the same device:</b>
<ul><li>Open two different browser windows or tabs and navigate to http://localhost:3000 in both.</li>
<li>Each player can play alternately as White and Black.</li></ul>

<h1>How to Play</h1>
<ol>
  <li>Once both players are connected, the game will automatically assign one player to White and the other to Black.</li>
<li>The game follows standard chess rules, and players must take turns making their moves.</li>
<li>The game communicates each move in real-time, ensuring both players see the updated board simultaneously.
</li>
</ol>

Future Enhancements
Adding more features such as online play, AI opponents, and advanced game analytics.
