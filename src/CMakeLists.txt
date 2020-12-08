include_directories(${CMAKE_CURRENT_SOURCE_DIR})

add_subdirectory(kml)


if(WITH_SWIG)
add_subdirectory(swig)
endif()

set(LIBKML_TARGETS "${LIBKML_TARGETS}" PARENT_SCOPE)