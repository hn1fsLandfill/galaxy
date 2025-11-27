project('spacecpp', 'c', 'cpp')

opengl_dep = dependency('gl')
glfw3_dep = dependency('glfw3')

inc = include_directories('Source', 'glad/include' )

executable('spacecpp', 
  'Source/BlackHole.cpp',
  'Source/Camera.cpp',
  'Source/FontRenderer.cpp',
  'Source/GalacticGas.cpp',
  'Source/Input.cpp',
  'Source/main.cpp',
  'Source/SolarSystem.cpp',
  'Source/Stars.cpp',
  'Source/UI.cpp',
  'Source/Window.cpp',
  'glad/src/glad.c',
  include_directories: inc,
  dependencies: [opengl_dep, glfw3_dep]
)
