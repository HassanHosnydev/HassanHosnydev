# Horizon Contact Center

A multi-tenant contact center platform with browser-based VoIP/SIP calling.

**My role:** Front-End Developer

## The work

The platform lets agents make and receive calls in their browser. The interface needs to keep call state clear while supporting separate organizations and different agent and administrator permissions.

I built the softphone interface and call lifecycle UI with React and TypeScript, integrating SIP.js and WebRTC for browser-based calling. I worked on real-time call state, including handling network interruptions and page reloads.

I also developed agent and administrator workspaces, a visual IVR builder, and PBX administration interfaces for DIDs, queues, and IVR provisioning. These interfaces connect to authentication, PBX, and signaling APIs.

## Technical work

- React and TypeScript for the application interface.
- SIP.js and WebRTC for browser calling.
- Zustand for application state and WebSockets for real-time updates.
- URL-scoped organizations and role-aware workspaces for the multi-tenant interface.
- Call lifecycle handling across connection changes.

## Source

The production source code is held in private company repositories. This page documents my frontend contribution.
