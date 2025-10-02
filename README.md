# Quizkampen

## Description
Quizkampen is a two-player, turn-based quiz game where players compete across multiple categories. In each round, players take turns selecting a category, 
and both players answer the same questions. The game requires real-time coordination as players must wait for their opponent to complete their turn before proceeding.

![quizkampenbild](https://github.com/user-attachments/assets/8ae1fd21-8650-46ee-8cdc-1b5518c039ff)

## Technology Stack & Architecture
The entire application is written in **Java**. 
* **Frontend (GUI):** Built using **Java Swing** components and various layout managers.
* **Backend (Network):** Uses a **Client-Server architecture**. A dedicated ServerListener handles the game state, question flow, and communication with the two connected client applications.

## How to run the game
1. Clone the repository.
2. Compile the Java files.
3. Run the ServerListener class.
4. Run the Client class twice (two separate windows/consoles) to start the game.

## Known issues
The scoring display logic is currently inconsistent, which causes incorrect point totals to be shown to the players between rounds
