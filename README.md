🇫🇷 FrenchLearn Mastery Ecosystem
Hero ImageReactSupabaseTailwindFramer

The ultimate open-source ecosystem for mastering French from A1 to C2.


View Demo
 • Report Bug • Request Feature

👋 About the Project
FrenchLearn is a premium, high-fidelity language learning application built to mirror the world's top educational apps. Unlike generic tools, FrenchLearn combines a gamified learning path with advanced specialty suites for linguistic mastery.

✨ What makes it different?
Institutional Strength: Curriculum aligned with the official CEFR Framework.
Scientific Retention: Proprietary Spaced Repetition System (SRS) built directly into the core.
Interactive Simulations: Real-time AI-powered dialogue and writing correction.
🚀 Key Features
🗺️ The Learning Path
Experience the Duolingo-style roadmap. A segmented, staggered-node visualization that guides you through every step of your journey with fluid animations and progress tracking.

🧠 The Mastery Hub
A dedicated ecosystem for targeting specific skill gaps:

🔥 Battle Arena: Timed high-speed translation tests.
🔬 Grammar Lab: Diagnostic drills for high-level sentence structure.
💬 Dialogue Simulator: Branching conversational scenarios with audio.
✍️ Writing Lab: Guided DALF-aligned essay builder.
📊 Real-time Analytics
A proactive dashboard featuring Liquid Progress Tracking, Streak Challenges, and Achievement Badges.

💻 Tech Stack
Core: React.js + Vite
Language: TypeScript
Database/Auth: Supabase
Styling: Tailwind CSS
Animations: Framer Motion
Icons: Lucide React
📂 Project Structure
text
├── src/
│   ├── components/       # Reusable UI (PathNodes, Dialogs, etc.)
│   ├── hooks/            # Custom Logic (useSRS, useDashboard)
│   ├── integrations/     # Supabase client & types
│   ├── pages/            # View components (Mastery, Levels, Games)
│   └── lib/              # Utility functions
├── supabase/
│   └── migrations/       # SQL relational schema & curriculum seeding
└── public/               # Static assets & audio
🛠️ Quick Start
Clone & Install

bash
git clone https://github.com/yourusername/frenchlearn.git
cd frenchlearn
npm install
Environment Setup Create a .env file in the root:

env
VITE_SUPABASE_URL=your_url
VITE_SUPABASE_ANON_KEY=your_key
Run Development Server

bash
npm run dev
Built for the future of language education.


