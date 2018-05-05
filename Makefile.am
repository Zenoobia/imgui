# IMGUI
include $(top_srcdir)/Makefile.common

AM_CFLAGS += $(GL_CFLAGS)

AM_CPPFLAGS += -I$(top_srcdir)/third_party/repos/imgui -I$(top_srcdir)/third_party/repos/imgui/examples/libs/glfw/ -I$(top_srcdir)/third_party/repos/ -I$(top_srcdir)/src/ -std=c++11

noinst_HEADERS = imgui.h examples/sdl_opengl3_example/imgui_impl_sdl_gl3.h examples/sdl_opengl2_example/imgui_impl_sdl.h
noinst_LTLIBRARIES = libImgui.la

libImgui_la_LDFLAGS = -version-info 0:0:0
libImgui_la_SOURCES = imgui.cpp imgui_draw.cpp examples/opengl3_example/imgui_impl_glfw_gl3.cpp examples/opengl2_example/imgui_impl_gl2.cpp



