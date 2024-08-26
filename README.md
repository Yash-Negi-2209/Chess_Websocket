# Real-Time Multiplayer Chess Game

## Overview

This project is a real-time, multiplayer chess game built using Node.js, Express, and Socket.IO. The game allows two players to play a traditional game of chess over the web, with real-time communication and game state updates.

## Features

- **Real-Time Multiplayer**: Players can create or join rooms and play against each other in real-time.
- **Standard Chess Rules**: The game follows the standard rules of chess, including special moves like castling, en passant, and pawn promotion.
- **Socket.IO Integration**: Provides real-time updates and communication between players using WebSockets.
- **Interactive UI**: A user-friendly interface with a drag-and-drop functionality to move pieces, built with HTML, CSS, and jQuery.
- **Responsive Design**: The game board adjusts to different screen sizes for optimal user experience.

## Technical Stack

- **Backend**: Node.js with Express.js for managing HTTP requests, routing, and WebSocket connections.
- **Frontend**: HTML, CSS, and jQuery for rendering the chessboard and handling user interactions.
- **WebSockets**: Socket.IO for real-time communication, ensuring that both players see the same game state simultaneously.
- **Chessboard.js**: Used for rendering the chessboard and pieces, along with handling piece movements.
- **chess.js**: A JavaScript library that handles chess rules, move validation, and game state management.

## Game Rules

### Chess Basics
- **Objective**: The game aims to checkmate your opponent's king, meaning the king is under threat of capture and cannot escape.
- **Pieces**: Each player controls 16 pieces: 1 King, 1 Queen, 2 Rooks, 2 Bishops, 2 Knights, and 8 Pawns.
- **Movement**: Each type of piece has specific movement rules (e.g., rooks move in straight lines, bishops move diagonally).
- **Special Moves**: The game supports castling, en passant, and pawn promotion.

### Gameplay
- **Turn-Based**: Players alternate turns, moving one piece per turn.
- **Valid Moves**: The game only allows legal moves according to standard chess rules.
- **Check and Checkmate**: The game checks for check and checkmate conditions after every move.
- **Draw Conditions**: The game also checks for draw conditions, such as stalemate, threefold repetition, and insufficient material.

## Installation and Setup

### Prerequisites
- Node.js and npm installed on your machine.
