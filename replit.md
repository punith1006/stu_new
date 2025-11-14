# AI Education Suite

## Overview
This is a static website showcasing an AI Education Suite Demo System. It features a sidebar navigation that loads different educational products in an iframe viewer.

## Project Structure
- `index.html` - Main application file with embedded styles and JavaScript
- `superui.html` - Original HTML file (preserved)
- `styles.css` - Additional CSS styles (preserved)
- `server.js` - Simple Node.js HTTP server to serve the static files

## Features
- **Dynamic Testing**: Adaptive assessment platform (external iframe)
- **AI Chat Assistant**: Full-featured chat interface with:
  - User authentication (hardcoded demo credentials)
  - WebSocket-based streaming responses
  - Markdown rendering support
  - Bot selection (i-science / AI)
  - Theme toggle (light/dark mode)
  - Real-time message streaming
- Animated background with floating particles and grid overlay
- Glass morphism design with Frutiger Aero-style aesthetics
- Sidebar navigation for switching between different education products
- iframe-based content viewer
- Loading states and smooth animations

## Technology Stack
- Pure HTML/CSS/JavaScript (no frameworks)
- Node.js HTTP server for serving static files
- Responsive design

## Recent Changes
- Added AI Chat Assistant feature with WebSocket-based streaming chat (Nov 14, 2025)
- Created `chat.html` with login, chat interface, and markdown rendering (Nov 14, 2025)
- Integrated with external backend API at globalknowledgetech.com (Nov 14, 2025)
- Created `index.html` as the main entry point (Nov 14, 2025)
- Added simple Node.js server for development (Nov 14, 2025)
- Configured workflow to run on port 5000 (Nov 14, 2025)

## Development
The site runs on port 5000 using a simple Node.js HTTP server with caching disabled for development.
