# mandelbrot-imgui

Render high-resolution images of the Mandelbrot set, with a GUI backed by imgui

Mainly a project to learn how to integrate imgui into applications to provide
live previews and debug information during a live render

# How to Build

To run the renderer:
```
git clone https://github.com/nathanlo99/mandelbrot-imgui --recurse-submodules
cd imgui-cmake
git submodule foreach git pull origin HEAD
mkdir build && cd build
cmake -D BUILD_EXAMPLES=ON ..
cmake --build . -j4
./mandelbrot
```
