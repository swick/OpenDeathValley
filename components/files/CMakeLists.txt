
set(ODV_FILES_SRC
    odv_file.c
    odv_fxg_handler.c
    odv_resource_handler.c
    odv_resource_text.c
    odv_resource_wave.c
    odv_scb_disassembler.c
    odv_scb_handler.c
    odv_utils.c)

add_library(odv_component_files ${ODV_FILES_SRC})

