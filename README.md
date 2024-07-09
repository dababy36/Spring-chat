Chat Application

This is a simple chat application built using Spring Boot and WebSocket. The application allows users to create chat sessions with unique IDs and passwords. It also supports real-time chat messaging within these sessions.
Features

    Create chat sessions with specific IDs and passwords.
    View all available chat sessions.
    Real-time messaging using WebSocket.

Technologies Used

    Spring Boot
    WebSocket (STOMP)
    SockJS (client-side)

How to Run

    Ensure you have Java 19 and Maven installed.
    Build the project using mvn clean install.
    Run the application using mvn spring-boot:run.
    Access the application at http://localhost:8000.

Usage

    Use the REST API to create chat sessions and view available sessions.
    Connect to the WebSocket endpoint to join chat sessions and send messages in real-time.
