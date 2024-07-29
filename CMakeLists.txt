# matth-x/MicroOcppMongoose
# Copyright Matthias Akstaller 2019 - 2023
# MIT License

cmake_minimum_required(VERSION 3.15)

if(ESP_PLATFORM)

    idf_component_register(INCLUDE_DIRS "src")

    return()
endif()