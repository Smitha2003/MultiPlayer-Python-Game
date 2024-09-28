Rock-Paper-Scissors Game
Description
This is a multiplayer Rock-Paper-Scissors game implemented in Python using Pygame for the client interface and socket programming for the server-client communication. Players can connect and play against each other.

Files
client.py: Contains the Pygame client logic, including UI and game interactions.
game.py: Manages the game state, player moves, and determines the winner.
network.py: Handles the network connection between the client and the server.
server.py: Manages multiple client connections and game instances on the server side.
Installation
Ensure you have Python installed on your machine.

Install Pygame if you haven't already:

Running the Game
Start the server by running server.py.
Start the client by running client.py.

How to Play
Click on the "Rock", "Paper", or "Scissors" buttons to make your move.
Wait for the opponent to make their move.
The winner will be displayed on the screen after both players have made their selections.

Networking
Connection Details
Server Address: "" (Update to your actual server's IP if different)
Port: 5555

Important Classes
Network: Manages client-server communication.
