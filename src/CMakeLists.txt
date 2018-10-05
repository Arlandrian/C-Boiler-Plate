set(CMAKE_C_FLAGS "-Wall -g")

file( GLOB SRCS *.c *.h )

set( EXECUTABLE_OUTPUT_PATH "../" )

add_executable( ${PROJECT_NAME} ${SRCS} )
