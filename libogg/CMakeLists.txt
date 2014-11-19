set(OGG_SOURCES
    src/framing.c
    src/bitwise.c)

include_directories(.)
include_directories(include)
include_directories(include/ogg)

add_library(ogg ${OGG_SOURCES})