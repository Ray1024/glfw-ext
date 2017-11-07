# GLFW-ext

## Introduction

This is a extra library of glfw from http://www.glfw.org/ 
(Only for version 3.1.2 for now.).</br>
The extra feature is that you can create a glfw object and its associated context
 by with existing native handles. 
That solved many problems. Such as, render on a child window, render on a unknown
window but handle, etc.

## extra functions

### glfwCreateWindowEx(void* winHwnd, int width, int height, const char* title, GLFWmonitor* monitor, GLFWwindow* share);
brief : Creates a glfw window object and its associated context by with existing native handles.
param 1 : handle of the existing window.
param 2 : width The desired width, in screen coordinates, of the window. This must be greater than zero.
param 3 : height The desired height, in screen coordinates, of the window. This must be greater than zero.
param 4 : title The initial, UTF-8 encoded window title.
param 5 : monitor The monitor to use for full screen mode, or `NULL` to use windowed mode.
param 6 : share The window whose context to share resources with, or `NULL` to not share resources.
return : returns the object of glfw.

## the prebuilt lib file


## Compiling GLFW

See the [Compiling GLFW](http://www.glfw.org/docs/latest/compile.html) guide in
the GLFW documentation.
