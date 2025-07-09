cmake_minimum_required(VERSION 3.20.0)
find_package(Zephyr REQUIRED)
project(bitdog_button_blinky)

target_sources(app PRIVATE src/main.c)
