# Quick Start Guide - Minecraft Clone

## Prerequisites
- Node.js (v12 or higher)
- npm (Node Package Manager)

## Getting Started

1. Clone the repository or download the project files

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
# To run on default port 3000
npm start

# To run on port 3001
PORT=3001 npm start
```

## Game Controls

- **Movement**: W, A, S, D keys
- **Jump**: Space bar
- **Place block**: Left click
- **Remove block**: Alt + Left click
- **Select blocks**: Number keys 1-5
  - 1: Grass
  - 2: Wood
  - 3: Log
  - 4: Glass
  - 5: Dirt

## Troubleshooting

If port 3000 is already in use, you can:
1. Either accept the prompt to use another port
2. Or explicitly set the port using: `PORT=3001 npm start`

## Additional Information
This is a Minecraft clone built with:
- React
- Three.js
- React Three Fiber
- React Three Drei
- Zustand for state management 