# Hotspot

🗺️ **Live App**: [https://hotspotapp.vercel.app/](https://hotspotapp.vercel.app/)

A real-time, location-based messaging app where users join location-specific group chats and vote on new hotspot locations to be added to the map.

## Tech Stack

- **Backend**: Java 21, Spring Boot, MongoDB Atlas, WebSockets (STOMP over SockJS)
- **Frontend**: React, TypeScript, Vite, Tailwind CSS, shadcn/ui, MapBox

## Repository Structure

This repo contains both components as submodules:

- **Backend** ([`LINK`](https://github.com/jrustom/hotspot-server)) - REST API and WebSocket server
- **Frontend** ([`LINK`](https://github.com/jrustom/hotspot-ui)) - React web application

## Setup

See individual component READMEs for detailed setup:
- [Backend README](https://github.com/jrustom/hotspot-server/README.md)
- [Frontend README](https://github.com/jrustom/hotspot-ui/README.md)

## Quick Start

1. Clone with submodules: `git clone <repo-url> && cd hotspot && git submodule update --init --recursive`
2. Start backend: `cd backend && mvn spring-boot:run`
3. Start frontend: `cd frontend && npm install && npm run dev`
