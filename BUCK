cxx_library(
  name = 'imgui',
  header_namespace = '',
  exported_headers = [
    'imgui.h',
    'imconfig.h',
    'imgui_internal.h',
  ],
  srcs = [
    'imgui.cpp',
    'imgui_draw.cpp',
    'imgui_widgets.cpp',
    'imgui_demo.cpp',
  ],
  visibility = [
    'PUBLIC',
  ],
)

cxx_library(
  name = 'demo',
  header_namespace = '',
  srcs = [
    'imgui_demo.cpp',
  ],
  deps = [
    '//:imgui',
  ],
  visibility = [
    'PUBLIC',
  ],
)
