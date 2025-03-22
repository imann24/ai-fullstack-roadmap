# Full-Stack Developer Roadmap Visualization

An interactive visualization of the journey to becoming a full-stack developer in 2025, built with TypeScript, Tailwind CSS, Parcel, and Mermaid.js.

## Features

- Interactive flowchart diagram showing the full-stack development path
- Detailed information for each step in the roadmap
- Resource links for learning each technology or concept
- Modern, responsive UI for desktop and mobile viewing

## Technologies Used

- TypeScript
- Tailwind CSS
- Parcel (for bundling)
- Mermaid.js (for flowchart generation)

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- Yarn (v1.22 or higher)

### Installation

1. Clone the repository
2. Install dependencies:

```bash
yarn install
```

3. Start the development server:

```bash
yarn start
```

4. Open your browser and navigate to `http://localhost:1234`

## Building for Production

To build the application for production, run:

```bash
yarn build
```

The built files will be in the `dist` directory.

## Project Structure

```
├── src/
│   ├── index.html       # Main HTML file
│   ├── index.ts         # Main TypeScript file
│   ├── roadmap-data.ts  # Data for the roadmap
│   ├── styles.css       # Tailwind CSS styles
│   └── types.ts         # TypeScript type definitions
├── package.json
├── tailwind.config.js
├── postcss.config.js
├── tsconfig.json
└── README.md
```

## License

MIT 
