FT_Transcendence

FT_Transcendence is a cutting-edge, full-stack web application that combines modern technologies to deliver a seamless and interactive user experience.
Features

    Full-Stack Architecture: 
        Built with Django REST API for the backend and React for the frontend.
    Secure Authentication:
        Integrated OAuth 2.0 for user authentication and data retrieval.
    Real-Time Interactivity:
        Includes WebSockets for live chat functionality and an interactive Pong game.
    Blockchain Integration:
        Game results are securely stored on the blockchain using Ganache.
    Containerization:
        Ensures consistent development and deployment with Docker.
    Optimized Performance:
        Configured Nginx as a reverse proxy for efficient performance and secure HTTPS handling.

Technology Stack

    Backend: Django
    Frontend: React, BootStrap 5, ReactStrap
    Database: PostgreSQL
    Blockchain: Ganache
    DevOps: Docker, Nginx

Setup and Installation
Prerequisites

    Docker and Docker Compose installed
    Node.js and npm installed
    Python 3.8+

Installation

    Clone the Repository:

    git clone https://github.com/MehdiMirzaie2/ft_transcendence.git  
    cd ft_transcendence  

Environment Variables:
Populate the .env.dev file in the project root and configure the necessary variables. 

Start the Application:
Use Docker Compose to build and start the containers.

    terminal 1
        docker compose watch
    terminal 2
        docker compose up
    or run
        make

    Access the Application:
    The application will be available at https://localhost

Usage
Pong Game

    Access the interactive Pong game from the dashboard and compete in real-time.
    Game results are logged and stored securely on the blockchain.

Chat System

    Engage in live conversations with other users via WebSockets.

Contributing

Contributions are welcome! Please fork the repository, create a feature branch, and submit a pull request.