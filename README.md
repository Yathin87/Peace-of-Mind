Peace of Mind 🌿
A low-friction, AI-powered daily task manager and habit tracker designed to eliminate administrative friction.

What is this project?
Staying organized shouldn't feel like a chore. Traditional productivity apps force you to click through endless menus, calendar widgets, and dropdown boxes just to log a single task.

Peace of Mind removes that frustration. Instead of filling out rigid forms, you simply type what you want to do in everyday, natural language. An intelligent AI agent reads your sentence, automatically figures out what category it belongs to, and organizes your day for you.

Why does it matter?
Zero Friction: No manual form-filling or calendar clicking required. Just type your thought and press enter.

Smart Categorization: The system automatically sorts your tasks so you can focus on doing them rather than organizing them.

Forgiving Streaks: Life gets busy. The built-in 50% rule means your habit streaks won't completely reset if you miss minor tasks on heavy days, keeping you motivated instead of stressed.

How it Works (The User Journey)
Open the Dashboard: You land on a clean screen showing your daily progress ring.

Type Your Task: You write your goal naturally (e.g., "Finish project report tomorrow").

Automatic Magic: The system securely processes your text using AI via a safe backend proxy, extracts the important details, and saves it.

Track & Progress: Tasks appear instantly under their correct tabs. Checking them off fills up your daily progress ring and builds consistency.

Behind the Scenes (Simple Technical Overview)
The application is structured into three lightweight layers:

The Frontend: Built using clean HTML, CSS, and Vanilla JavaScript for instant browser loading and local state management.

The Backend & AI Proxy: Powered by a Supabase Edge Function that routes natural language securely through AI agents without exposing API keys.

The Database: Powered by Supabase (PostgreSQL) to safely store core tasks and separate them from date-specific completion logs.
