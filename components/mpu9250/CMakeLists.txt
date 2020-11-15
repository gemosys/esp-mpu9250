# Edit following two lines to set component requirements (see docs)
#set(COMPONENT_REQUIRES )
#set(COMPONENT_PRIV_REQUIRES )

set(COMPONENT_SRCS "mpu9250.c" "i2c-easy.c" "common.c" "calibrate.c" "ak8963.c")
set(COMPONENT_ADD_INCLUDEDIRS "")

register_component()