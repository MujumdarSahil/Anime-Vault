# Anime-Vault
A Next.js 14 server-side application featuring Actions, Infinite Scroll, and Framer Motion Animations.
![1](https://github.com/user-attachments/assets/67c4395b-0808-43e3-a0f4-c2b9a40aaa09)
![2](https://github.com/user-attachments/assets/403a2896-132e-4e45-8a83-ff9dae3ed7b1)


Table of Contents
Overview
Features
Demo
Getting Started
Prerequisites
Installation
Usage
Project Structure
Technologies Used
Contributing
License
Contact
Overview
Anime Vault is a web application built with Next.js 14 that displays a dynamic list of anime titles. It utilizes server-side rendering, Next.js Actions for efficient data fetching, infinite scrolling for seamless content loading, and Framer Motion for smooth animations.

Features
Server-Side Rendering: Enhances performance and SEO by rendering pages on the server.
Next.js Actions: Implements server-side functions for data fetching and state management.
Infinite Scroll: Automatically loads more anime cards as the user scrolls down.
Framer Motion Animations: Provides interactive and smooth animations for UI components.
Responsive Design: Ensures optimal viewing experience across a wide range of devices.
Getting Started
Follow these instructions to set up the project on your local machine.

Prerequisites
Node.js (v14 or later)
npm (v6 or later)
Git
Installation
Clone the Repository

bash
Copy code
git clone https://github.com/yourusername/anime-vault.git
cd anime-vault
Install Dependencies

bash
Copy code
npm install
Set Up Environment Variables

Create a .env.local file in the root directory and add necessary environment variables.

env
Copy code
NEXT_PUBLIC_API_URL=https://api.example.com
Usage
Running the Development Server
bash
Copy code
npm run dev
Visit http://localhost:3000 in your browser to view the application.

Building for Production
bash
Copy code
npm run build
Starting the Production Server
bash
Copy code
npm start
