PopX App - ReactJS Qualifier Task
A pixel-perfect, mobile-centered React application built as a qualifier task for the Educase ReactJS Internship.

The application strictly adheres to the provided Adobe XD design constraints, featuring seamless routing, custom interactive UI elements, and a clean component architecture.

🚀 Live Demo
[Insert your Vercel Hosted Link Here]

✨ Key Features
Pixel-Perfect UI: Accurately translates the Adobe XD design into code, maintaining precise spacing, typography, and the distinct PopX color palette.

Mobile-First Wrapper: Enforces a strict 375x812px mobile application view centered dynamically within the desktop browser window.

Seamless Routing: Utilizes react-router-dom for instant, page-reload-free navigation between the Landing, Login, Signup, and Profile screens.

Dynamic State Management: Captures user input on the Login/Signup screens and passes the data via router state to dynamically populate the Profile screen.

Custom UI Components: * Reusable InputField components utilizing native <fieldset> tags for accessible, floating-label borders.

Custom-built radio buttons for the "Agency" selection that natively match the design without relying on external component libraries.

🛠️ Tech Stack
Frontend Framework: React.js

Build Tool: Vite (v7)

Styling: Tailwind CSS (v4)

Routing: React Router DOM

Deployment: Vercel

💻 Local Development Setup
To run this project locally, ensure you have Node.js installed, then clone the repository and run the following commands:

Bash
# Clone the repository
git clone [Insert your GitHub Repo Link Here]

# Navigate into the project directory
cd popx-app

# Install dependencies (legacy-peer-deps required for Vite 7 / Tailwind v4 compatibility)
npm install --legacy-peer-deps

# Start the local Vite development server
npm run dev
👨‍💻 Author
Soumilya Roy
