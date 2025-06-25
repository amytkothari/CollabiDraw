🧠 Collaborative Board – Collaborate Visually, in Real Time

Collaborative Board is a modern whiteboard collaboration tool designed for seamless real-time drawing and brainstorming. Think of it as your digital space for team ideation, planning, and visual communication — inspired by tools like Excalidraw and Miro, but tailored for real-time interactivity and simplicity.

⸻

🚀 What You Can Do with CollabiDraw

✨ Sketch Freely
	•	Draw with pencils, create shapes, erase mistakes, undo/redo changes, or clear the canvas entirely.

🔐 Control Your Space
	•	Start or join whiteboard rooms — public for open collaboration, or private for secure sessions.

👥 Invite Others, Work Together
	•	Draw and brainstorm in real-time with others via WebSockets (Socket.io).

🖼️ Persistent Workspaces
	•	Your whiteboard data is saved with Firestore, so you can leave and return without losing progress.

🧠 Simple Yet Powerful UI
	•	Clean, responsive design powered by Tailwind CSS and ShadCN UI components.

⸻

🧰 Technology Overview

⚙️ Frontend
	•	React + Vite for a fast and modern development experience
	•	Tailwind CSS for utility-first responsive styling
	•	ShadCN UI to keep components consistent and accessible
	•	Zustand for smooth global and local state handling
	•	Socket.io Client for real-time interaction
	•	Axios for efficient API communication

🔧 Backend
	•	Node.js + Express for scalable server-side logic
	•	TypeScript ensures type safety and better maintainability
	•	Socket.io to enable WebSocket-based real-time data sync
	•	Firebase Admin SDK to manage authentication and database integration
	•	Cloud Firestore for storing room data and canvas state
	•	Firebase Storage (optional) for saving high-resolution snapshots

⸻

🔒 Authentication & Security
	•	Firebase Authentication manages secure user sign-ins with JWT
	•	Protected backend routes with middleware to validate user tokens and permissions

⸻
