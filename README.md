# 3D Tic Tac Toe Game

An innovative 3D Tic Tac Toe game built with React and React Three Fiber. This project was bootstrapped from an Educative.io template, with additional updates and modifications made to create a visually engaging 3D gaming experience using React Three Fiber.

## Features

- Classic 3x3 Tic Tac Toe gameplay in a 3D environment
- Interactive 3D game grid with orbit controls
- Player turn indicators (Sphere vs Cube)
- Win detection and 3D winner line visualization
- Orbit controls for viewing the game from different angles
- Environment lighting and background
- Responsive 3D design that works well on different screen sizes

## Technologies Used

- **React**: JavaScript library for building user interfaces
- **React Three Fiber**: React renderer for Three.js
- **Drei**: Useful helpers for React Three Fiber
- **Three.js**: 3D library for web browsers
- **Vite**: Next-generation frontend build tool
- **HTML5/CSS3**: Markup and styling
- **JavaScript (ES6+)**: Modern JavaScript features

## Project Origin

This project was originally bootstrapped from an Educative.io template and has been updated with custom 3D functionality using React Three Fiber. The build process has been configured to use Vite for faster development and optimized production builds.

## Getting Started

### Prerequisites

- Node.js (version 14 or higher)
- npm or yarn package manager

### Installation

1. Clone this repository or download the source code
2. Navigate to the project directory:

```bash
cd three-js-tic-tac-toe
```

3. Install the required dependencies:

```bash
npm install
```

### Running the Development Server

To start the development server and begin playing the game:

```bash
npm run dev
```

The application will open in your default browser at `http://localhost:5173` (or another port if 5173 is in use).

### Building for Production

To create an optimized production build:

```bash
npm run build
```

This will generate the production-ready files in the `dist` directory.

### Running the Production Build Locally

To serve the production build locally:

```bash
npm run preview
```

## How to Play

1. The game starts with Player Sphere's turn
2. Click on any empty 3D grid position to place your mark (Sphere or Cube)
3. Players alternate turns placing Spheres and Cubes
4. The first player to get 3 of their marks in a row (horizontally, vertically, or diagonally) wins
5. If all positions are filled with no winner, the game ends in a draw
6. Use your mouse to orbit around the 3D game board to view it from different angles

## Project Structure

```
├── public/              # Static assets
├── src/                 # Source code files
│   ├── components/      # 3D React components (SphereMesh, CubeMesh, GridBox, etc.)
│   ├── styles/          # CSS files
│   ├── App.jsx          # Main 3D application component
│   └── main.jsx         # Entry point of the application
├── index.html           # Main HTML file
├── package.json         # Project metadata and dependencies
├── vite.config.js       # Vite configuration
└── README.md            # This file
```

## Customizations Made

While the project originated from an Educative.io template, the following updates were made:

- Integration with React Three Fiber for 3D rendering
- Implementation of 3D game components (Spheres and Cubes)
- Addition of orbit controls for 3D camera manipulation
- Integration with Drei for useful 3D helpers
- Environment lighting and background setup
- Integration with Vite for faster development and building
- Modern React implementation with hooks
- Enhanced 3D styling and responsive design
- Game logic implementation and improvements
- Project structure optimization

## Contributing

If you'd like to contribute to this project:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is open-source and available under the MIT License.

## Acknowledgments

- Bootstrapped from an Educative.io template
- Created using React and React Three Fiber for a modern 3D web development experience
- Utilizes Three.js and Drei for enhanced 3D capabilities
- Inspired by classic Tic Tac Toe games and their strategic gameplay

---

_Project maintained by Abbiirr. Built with React and Vite._
