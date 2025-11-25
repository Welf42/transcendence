# transcendence

## Requirements
- Typescript
- Mozilla Firefox
- Docker
- SPA (Single Page Application)

## Game
- Play on one keyboard (Remote Players module)
- Tournament
- Registration system with alias (Standard User Management module)
- matchmaking system
- identical paddle speed (also for ai)
- Frontend constraints [Typescript] (Frontend & Graphics module)

## Security
- Passwords in DB must be hashed
- Website protected against SQL injections/XSS
- HTTPS connection for all aspects
- Validation mechanisms for forms and any user input
- API - - > ensure your routes are protected
- credentials, API keys, env variables etc., must be saved locally in a .env file 

## Modules 
###  Web
- Major module: Use a **framework** to build the **backend**. [Fastify with Node.js]
- Minor module: Use a **framework** or a toolkit to build the **frontend**. [TailwindCSS]
- Minor module: Use a **database** for the **backend**. [SQLite]
- Major module: Store the score of a tournament in the **Blockchain**. [Avalanche with Solidity]
### User Management
- Major module: **User Mgmt**: Standard user management, authentication, users across [?]
tournaments.
- Major module: Implementing a **remote authentication**. [OAuth 2.0]
### Gameplay and user experience
- Major module: Remote players
- Major module: Multiplayer (more than 2 players in the same game).
- Major module: Add another game with user history and matchmaking.
- Minor module: Game customization options.
- Major module: Live chat.
### AI-Algo
- Major module: Introduce an AI opponent.
- Minor module: User and game stats dashboards
### Cybersecurity
- Major module: Implement WAF/ModSecurity with a hardened configura- 
tion and HashiCorp Vault for secrets management.
- Minor module: GDPR compliance options with user anonymization, local
data management, and Account Deletion.
- Major module: Implement Two- Factor Authentication (2FA) and JWT.
### Devops
- Major module: Infrastructure setup for **log management**. [ELK]
- Minor module: **Monitoring** system. [Prometheus and Grafana]
- Major module: Designing the **backend as microservices**. [Restful APIs]
### Graphics
- Major module: Use advanced **3D** techniques. [Babylon.js]
### Accessibility
- Minor module: Support on all devices.
- Minor module: Expanding browser compatibility.
- Minor module: Supports multiple languages.
- Minor module: Add accessibility features for visually impaired users.
- Minor module: Server- Side Rendering (SSR) integration.
### Server- Side Pong
- Major module: Replace basic Pong with server- side Pong and implement an
API.
- Major module: Enabling Pong gameplay via CLI against web users with
API integration.

# What would I do?
- Frontend Framework [Fastify with Node.js] (1)
- Backend Framework [TailwindCSS] (1/2)
- Database [SQLite] (1/2)
- Blockchain Score [Avalanche] (1)
- User Mgmt (1)
- Remote Authentification (1) 
- Log Mgmt [ELK] (1)
- Monitoring [Grafana, Prometheus] (1/2)
- Backend as microservices (1)
- 3D Graphics [Babylon.js] (1)
==> 8.5

# Personal Add-On
-D3.js for nice graphics