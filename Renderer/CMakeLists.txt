file(GLOB SOURCES *.cpp)
file(GLOB HEADERS *.h)

target_sources(shadertext PUBLIC ${HEADERS})
target_sources(shadertext PUBLIC ${SOURCES})
