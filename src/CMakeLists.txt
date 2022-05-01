
add_executable(mandelbrot)
target_sources(mandelbrot PUBLIC main.cpp)
target_link_libraries(mandelbrot IMGUI)
set_target_properties(mandelbrot PROPERTIES RUNTIME_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR})
