# EaseChat - Real-Time Chat Application

## Overview

EaseChat is a real-time chat application built using Node.js and Socket.io. It allows users to join specific chat rooms, send messages, and receive real-time updates about user activities within the room.

## Features

- **Room-Based Messaging**: Users can join specific chat rooms and communicate with others in the same room.
- **Real-Time Communication**: Messages are delivered instantly using Socket.io for seamless real-time interaction.
- **User Notifications**: Receive notifications when users join or leave the chat room.
- **User List Updates**: Live updates of users in the chat room displayed on the sidebar.

## Technologies Used

- **Backend**: Node.js, Express.js, Socket.io
- **Frontend**: HTML, CSS, JavaScript
- **Utilities**: Query String (Qs) library for parsing URL parameters

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/akashchandra9/EaseChat.git
   ```
2. Navigate to the project directory:
   ```
   cd easechat
   ```
3. Install the dependencies:
   ```
   npm install
   ```
4. Start the server:
   ```
   node app.js
   ```

## Usage

1. Open your browser and go to `http://localhost:3000`.
2. Enter your username and select a chat room.
3. Start chatting in real-time!

## Project Structure

- `app.js`: Main application file setting up the server and Socket.io.
- `public/`: Contains the static HTML, CSS, and JavaScript files.
- `utils/`: Utility functions for managing users and formatting messages.
