# Black Hole Simulation Project

This project aims to simulate the visual appearance and astrophysical environment of a black hole using advanced numerical methods and high-performance computing. The system is designed to handle both real-time interactive visualization and high-precision astrophysical ray tracing.

## Getting Started

1. **Clone the repository**:
   ```sh
   git clone https://github.com/your-repo/black-hole-simulation.git
   cd black-hole-simulation
   ```

2. **Install dependencies**:
   ```sh
   vcpkg install glfw3 glew glm cfitsio
   ```

3. **Build the project**:
   ```sh
   mkdir build
   cd build
   cmake ..
   make
   ```

4. **Run the GPU simulation**:
   ```sh
   ./BlackHole3D_GPU
   ```

5. **Run the CPU tracer**:
   ```sh
   ./BlackHole3D_CPU
   ```

6. **Run the 2D lensing tool**:
   ```sh
   ./BlackHole2D_Lensing
   ```

7. **Run the spacetime grid visualizer**:
   ```sh
   ./SpacetimeGrid
   ```

## Usage

The project consists of several components:
- **Real-time GPU Compute Engine**: Interactive 60 FPS viewport manipulation using OpenGL 4.3 Compute Shaders.
- **High-Precision CPU Tracer**: Double-precision scientific accuracy with adaptive RKF45/RKDP45 integration.
- **2D Interactive Lensing Tool**: Interactive light ray spawning and deflection angle verification.
- **Spacetime Grid Visualizer**: Dynamic 3D wireframe visualization of gravitational potential wells.

## Contributing

Feel free to contribute to this project by opening issues or pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
