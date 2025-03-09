# Shenkar College Matching Game

## Overview
This repository contains documentation for a drag-and-drop educational matching game created for Shenkar College. The game was developed under a tight deadline as a rapid prototype to enhance student learning through interactive engagement.

👉 **[Play the Game Live](https://shenkargame.web.app/)** 👈

## Project Context
I was contracted by Shenkar College to create an educational game with a short turnaround time. The goal was to develop an intuitive, engaging learning tool that could help students memorize important terminology through a matching exercise. The project required not only frontend development but also backend integration for tracking student progress and creating a competitive learning environment.

## Game Description
The game presents players with a 2×2 matrix of explanation cells. Players must drag the correct terminology onto the matching explanation. When correctly matched, a relevant image appears, providing visual reinforcement of the concept.

## Features

### Core Functionality
- **Drag and Drop Interface**: Intuitive drag-and-drop mechanics using React DnD
- **Dynamic Content Loading**: Game loads definitions from a CSV file
- **Real-time Feedback**: Visual highlighting when hovering over potential matches
- **Score Tracking**: Keeps count of correct and incorrect matches with persistent leaderboard
- **Firebase Backend**: Player scores stored in Firebase Realtime Database for analytics and competition
- **Visual Reinforcement**: Displays relevant images when matches are correct

### Technical Highlights
- Built with React.js
- CSV-driven content makes it easy to update terminology
- Responsive design works across different devices
- Clean, modern UI with visual feedback during interactions
- Lightweight and fast-loading

## Implementation Details
The game uses a component-based architecture with:
- CSV parsing to load game content dynamically
- React DnD for drag-and-drop functionality
- State management to track game progress
- CSS Grid for responsive layout
- Firebase Hosting for deployment (https://shenkargame.web.app/)
- Firebase Realtime Database for storing and retrieving player scores
- Authentication for score tracking and user identification

## Future Enhancements
While this version was developed under a tight deadline, potential future enhancements could include:
- Multiple difficulty levels
- Timed challenges
- Additional game modes
- Enhanced animations and sound effects
- Integration with learning management systems

---

*Note: This repository contains only the README documentation. The actual code is deployed directly to Firebase.*
