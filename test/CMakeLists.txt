option(BUILD_GMOCK "Builds the googlemock subproject" OFF)
option(INSTALL_GTEST "Enable instllation of googletest" OFF)

add_subdirectory(googletest)

find_package(GTest REQUIRED)

enable_testing()


