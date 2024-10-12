# Video Call React App
This is a video call application built with React that supports real-time video communication using WebRTC and socket.io. It allows users to initiate, accept, and reject calls, and handles multiple video streams between peers.

## Features
Real-time Video Calls: Peer-to-peer video calls using WebRTC.

Socket.io Integration: Manages signaling and connection between users.

Call Management: Users can start, accept, and reject calls.

Responsive UI: Simple and intuitive user interface for managing calls.

## Project Structure
-> App.js: Main component handling the state of the video call (calling, receiving, and ending).

-> components/MainWindow.js: Renders the main screen where users can start a call.

-> components/CallWindow.js: Displays the active call, showing both local and peer video streams.

-> components/CallModal.js: Modal that appears when a call is incoming, allowing users to accept or reject the call.

-> communication.js: Contains the WebRTC and socket connection logic for handling peer connections.
