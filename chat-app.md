# 💬 Chat-App

**GitHub Repository:** [gab-dev-7/chat-app](https://github.com/gab-dev-7/chat-app)

## Overview

A real-time, terminal-based chat application that enables communication over local networks with full chat room capabilities.

## Detailed Description

This CLI chat application provides a simple yet powerful way to communicate over networks with support for multiple rooms, user authentication, and message history.

## Installation

```bash
git clone https://github.com/gab-dev-7/chat-app.git
cd chat-app
pip install -r requirements.txt
```

## Usage Examples

# Start the chat server

python chat_server.py --port 8888 --host 0.0.0.0

# Connect as a client

python chat_client.py --server 192.168.1.100 --port 8888 --username alice

# Join specific room

python chat_client.py --server localhost --room general --username bob

## Features in Detail

- **Real-time Messaging**: Instant message delivery
- **Room Management**: Create and join multiple chat rooms
- **User System**: Basic authentication and user management
- **Message Persistence**: Chat history storage and retrieval

## Tech Stack Deep Dive

- **Python 3.6+**: Core application logic
- **Socket Programming**: Network communication
- **Threading**: Concurrent client handling
- **SQLite**: User and message data storage

[← Back to Overview](../)
