add_subdirectory(kml)

include_directories(kmlbase PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/)


if(WITH_SWIG)
add_subdirectory(swig)
endif()

set(LIBKML_TARGETS "${LIBKML_TARGETS}" PARENT_SCOPE)