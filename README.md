# JS Learning Hub

Master JavaScript fundamentals with 25 interactive coding challenges!
Write code, see results instantly, and track your progress as you build real programming skills.

## Features

- **25 Carefully Crafted Challenges**: Ranging from "Hello World" to advanced array and string operations.
- **Interactive Code Editor**: Write and execute JavaScript code in real-time with instant feedback.
- **Progress Tracking**: Mark challenges as complete and monitor your learning journey.
- **Certificate of Completion**: Finish all challenges to earn and download a personalized certificate.
- **Resource Library**: Access curated resources to deepen your JavaScript knowledge.
- **Modern UI**: Built with React, TypeScript, Tailwind CSS, and Vite for a fast, beautiful experience.

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v16 or higher recommended)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/jsapp.git
   cd jsapp
   ```

2. **Install dependencies:**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Start the development server:**
   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. **Open your browser:**
   Visit [http://localhost:5173](http://localhost:5173) (or the URL shown in your terminal).

### Build for Production

```bash
npm run build
# or
yarn build
```

### Preview Production Build

```bash
npm run preview
# or
yarn preview
```

## Project Structure

```
.
├── index.html                # Main HTML file (includes Google Analytics)
├── src/
│   ├── App.tsx               # Main app component
│   ├── main.tsx              # Entry point
│   ├── components/           # UI components (HomePage, CodeEditor, Certificate, etc.)
│   ├── data/questions.ts     # List of 25 JavaScript challenges
│   ├── utils/progress.ts     # Progress tracking logic
│   └── index.css             # Tailwind CSS styles
├── package.json
├── vite.config.ts
└── README.md
```

## Tech Stack

- **React** (with Hooks)
- **TypeScript**
- **Vite** (for fast development and build)
- **Tailwind CSS** (for styling)
- **Lucide React** (icons)
- **Monaco Editor** (code editing)
- **html2canvas** (certificate download)

## Analytics

Google Analytics is integrated via `gtag.js` in `index.html` for usage tracking.

## License

MIT

&copy; 2024 JS Learning Hub
