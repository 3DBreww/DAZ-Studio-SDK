# DAZ Studio SDK

This repository contains the official SDK for developing plugins and extensions for DAZ Studio, a professional 3D modeling and animation software platform.

## Project Structure
- **bin/** - Compiled binaries (Win32/x64)
- **docs/** - API documentation and reference materials
- **include/** - SDK header files
- **lib/** - Precompiled libraries
- **samples/** - Example plugins and usage demonstrations
- **CMakeLists.txt** - Build configuration for cross-platform compilation

## Prerequisites
- DAZ Studio 4.5+ installed
- CMake 3.15+
- Visual Studio 2019+ (Windows)
- Qt 5.15+ (for UI components)

## Building the SDK
1. Register the SDK environment:
   ```cmd
   register_SDK.bat
   ```
2. Configure the build:
   ```cmd
   mkdir build
   cd build
   cmake ..
   ```
3. Compile the project:
   ```cmd
   cmake --build . --config Release
   ```

## Using the SDK
1. Include necessary headers from `include/` directory
2. Link against libraries in `lib/`
3. Use the provided samples as starting points for your plugins

## Documentation
Complete API documentation is available in the `docs/` directory. Open `docs/index.html` in your browser for interactive documentation.

## Samples
The `samples/` directory contains several example plugins demonstrating:
- Basic plugin structure
- UI integration
- Asset management
- Scene manipulation
- Custom shader implementation

## Contributing
Contributions to the SDK are welcome! Please:
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License
This SDK is provided under the MIT License. See [LICENSE](LICENSE) for details.

---

*This SDK is maintained by the DAZ 3D development team. For support, please contact sdk-support@daz3d.com.*
