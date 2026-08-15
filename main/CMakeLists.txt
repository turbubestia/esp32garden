# This file was automatically generated for projects
# without default 'CMakeLists.txt' file.

SET(APP_SOURCES 
    main.c
)

idf_component_register(
    SRCS ${APP_SOURCES}
    PRIV_REQUIRES esp_http_server nvs_flash
)
