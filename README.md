# Global Datacenter Visualization

An interactive 3D globe visualization comparing centralized data centers and decentralized mesh nodes, built with Three.js. Demonstration of an interactive globe rendered using Three.js, complete with a starfield background and orbit controls. The globe uses custom shaders to apply textures, elevation, and alpha transparency.

## Features

- **Interactive Globe**: A rotating 3D globe built with an `IcosahedronGeometry`, wireframe, and point geometry using custom shaders.
- **Custom Shaders**: Vertex and fragment shaders are used for applying color, elevation, and alpha textures.
- **Starfield Background**: A dynamic starfield for added depth and visual appeal.
- **Orbit Controls**: Allows users to rotate and zoom the globe interactively using the mouse.
- **Responsive Design**: Automatically adjusts the canvas size when the window is resized.

## How to Run

1. Clone or download this repository to your local machine.
2. Open a terminal or command prompt and navigate to the project directory.
3. Make sure you have Node.js installed on your computer. If not, download and install it from nodejs.org.
4. In the project directory, run the following command:

npx http-server

This will start a local server. If it's your first time running this command, you might be prompted to install http-server. Accept the installation.
5. Once the server is running, you'll see a message with URLs. Open your web browser and go to one of these URLs, typically http://localhost:8080.
6. You should now see the Global Datacenter Visualization running in your browser.

**Note:** If port 8080 is already in use, http-server will automatically use the next available port.

## Usage

Use your mouse to interact with the globe:

- Click and drag to rotate
- Scroll to zoom in/out

Use keyboard controls:

- ress 'C' to toggle centralized data centers (red dots)
- Press 'D' to toggle decentralized mesh nodes (green dots)
- Press 'T' to toggle between cool textures and default earth textures

### Customization

- **Globe Appearance**: Modify the textures in the `TextureLoader` (`colorMap`, `elevMap`, and `alphaMap`) to change the appearance of the globe.
- **Starfield**: Adjust the number of stars or their size in `getStarfield.js` to change the look of the starfield.
- **Shaders**: Modify the vertex or fragment shaders for custom visual effects on the globe's surface.

## Demo deployment

[https://global-datacenter-visualizer.netlify.app/](https://global-datacenter-visualizer.netlify.app/)

### Acknowledgments

- [Three.js](https://threejs.org/) for the awesome 3D library.
- [Three.js Forum](https://discourse.threejs.org/) for shader examples and discussions.
- [Robot Bobby on YT](https://youtu.be/tBSzJstOGnM)
