# SyncFlix: Real-Time Watch Party Web App
> A collaborative web application designed for synchronized video streaming, live social interaction, and seamless media discovery.

## Project Overview
**SyncFlix** is a high-performance UI/UX concept built to solve the classic problem of watching videos apart while staying completely in sync. Whether hosting a movie night with friends or managing a large group viewing party, SyncFlix bridges the digital gap with low-latency playback controls, interactive social tools, and a theater-first design.

This project was fully conceptualized, wireframed, and designed in **Figma**, focusing heavily on multi-user collaboration, edge-case UI states (like late-joins and drift correction), and a distraction-free dark-themed viewing experience.

---

## View the Design
* **[🔗 View Interactive Figma Prototype](https://www.figma.com/design/S9I1ogHFbn9H4y9ZTlQvHO/Untitled?node-id=0-1&t=kKrOITpHnWkQ4s3i-1)**

---

## Key Features & User Flows

### 1. Room Creation & Management
* **Instant Onboarding:** Create or join private watch rooms effortlessly via unique invite links or short room codes.
* **Host Controls:** Clear indicators for room ownership with seamless host-transfer capabilities and participant management (supporting 10+ concurrent users per room).

### 2. Synchronized Theater Interface
* **Zero-Drift Playback:** UI design elements dedicated to real-time play, pause, and seek synchronization across all participants ($\le 250\text{ms}$ control propagation).
* **Drift Handling:** Visual alerts and auto-correction states to gracefully handle network lag or timeline discrepancies ($\le 500\text{ms}$).

### 3. Social & Interactive Layer
* **Live Sidebar Chat:** Integrated real-time messaging with custom emoji reactions floating across the video canvas.
* **Collaborative Tools:** Group polls for picking the next movie and a shared queue playlist manager.

### 4. Smart Media Discovery
* **Advanced Search:** Category filters, trending carousels, and fuzzy search capabilities to discover content quickly before launching a session.

---

## Design Highlights
* **Immersive Dark Theme:** Optimized for media consumption, reducing eye strain during long viewing sessions.
* **Responsive Layouts:** Split-screen architecture that keeps the video player front-and-center while keeping chat and participant drawers accessible.