add_library(ImGuiLib STATIC
    imgui_draw.cpp
    imgui_impl_glfw.cpp
    imgui_impl_opengl3.cpp
    imgui_tables.cpp
    imgui_widgets.cpp
    imgui_demo.cpp
    imgui.cpp
)

target_link_libraries(ImGuiLib glfw)