# Horizon Contact Center

A multi-tenant contact center platform with browser-based VoIP/SIP calling.

**My role:** Front-End Developer within a three-person team covering frontend, backend, and VoIP.

## The work

The platform lets agents make and receive calls in their browser. The interface needs to keep call state clear while supporting separate organizations and different agent and administrator permissions.

I built the softphone interface and call lifecycle UI with React and TypeScript, integrating SIP.js and WebRTC for browser-based calling. I worked on frontend call-state handling with the backend and VoIP specialists. This was shared system work, not sole ownership of the telephony stack.

I also developed agent and administrator workspaces, a visual IVR builder, and PBX administration interfaces for DIDs, queues, and IVR provisioning. These interfaces connect to authentication, PBX, and signaling APIs.

## Technical work

- React and TypeScript for the application interface.
- SIP.js and WebRTC for browser calling.
- Zustand for application state and WebSockets for real-time updates.
- URL-scoped organizations and role-aware workspaces for the multi-tenant interface.
- Call lifecycle handling across connection changes.

## Selected implementation history

| Date | Reference | Contribution recorded under HassanHosnydev |
| --- | --- | --- |
| 8 July 2026 | [f29ca86](https://github.com/Horizonz-tech/horizontech-it-call-center-fornt/commit/f29ca869bf0a9721ded5513db9b3c6d71abaa9e3) | Frontend call recovery and release handling to avoid conflicts across tabs, as recorded in the history. |
| 26 July 2026 | [c46e1b3](https://github.com/Horizonz-tech/horizontech-it-call-center-fornt/commit/c46e1b3fce29144336fc00fb5732d7ea432d0b88) | Hold/mute persistence and call-state reconciliation. The reviewed diff restores saved UI state for the matching call and prevents stale caller information from carrying over to another call. |
| 27 July 2026 | [05ef8c8](https://github.com/Horizonz-tech/horizontech-it-call-center-fornt/commit/05ef8c8092ba862af231a6a3c0198a033f4dc0e8) | Microphone-permission re-probing and audio probe state management, as recorded in the history. |
| 28 July 2026 | [0760dec](https://github.com/Horizonz-tech/horizontech-it-call-center-fornt/commit/0760decb32070e21c308bc8b29ab3039639a61fc) | Field-level validation and error feedback for tenant creation, as recorded in the history. |

## Verification and source access

The contribution history, package manifest, project documentation, and selected call-state diff were reviewed in the private company repository. SIP.js, Socket.io client, Zustand, React Hook Form, Zod, and TanStack Query are present in the package manifest.

Other contributors have separate VoIP and connection-recovery changes in the history. The references above document my contributions, not ownership of every change in the repository.

These commit links require authorized repository access and may return 404 for public visitors. They are traceable private references, not publicly accessible proof. No source code, credentials, customer information, or internal service addresses are reproduced here.
