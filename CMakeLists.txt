cmake_minimum_required(VERSION 3.5)
project(lingmo-grub-config)


install(DIRECTORY ${CMAKE_SOURCE_DIR}/boot

        DESTINATION / )

install(DIRECTORY ${CMAKE_SOURCE_DIR}/etc

        DESTINATION / )

install(DIRECTORY ${CMAKE_SOURCE_DIR}/usr

        DESTINATION / )


