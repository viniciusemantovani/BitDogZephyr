# SPDX-License-Identifier: Apache-2.0

cmake_minimum_required(VERSION 3.20.0)

find_package(Zephyr)
project(bitdog_helloworld)

target_sources(app PRIVATE src/main.c)