cmake_minimum_required(VERSION 3.16.0)

list(APPEND EXTRA_COMPONENT_DIRS .pio/libdeps/esp32dev/esp-idf-lib/components)

include($ENV{IDF_PATH}/tools/cmake/project.cmake)
project(esp32-demo)
