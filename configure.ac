dnl Process this file with autoconf to produce a configure script.

AC_PREREQ(2.59)
AC_INIT(Vulkan_Tutorials, 1.0)


AC_CANONICAL_SYSTEM
AM_INIT_AUTOMAKE()

PKG_CHECK_MODULES([vulkan], [vulkan])
PKG_CHECK_MODULES([glfw3], [glfw3])

AC_PROG_CXX

AC_CONFIG_FILES(Makefile src/first_window/Makefile src/triangle/Makefile)
AC_OUTPUT

