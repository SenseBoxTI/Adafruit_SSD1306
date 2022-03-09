cmake_minimum_required(VERSION 3.5)

idf_component_register(SRCS "Adafruit_SSD1306.cpp"
                       INCLUDE_DIRS "."
                       REQUIRES arduino adafruit_gfx_library)

project(adafruit-ssd1306)
