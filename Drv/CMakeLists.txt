# Module subdirectories

# Ports
add_fprime_subdirectory("${CMAKE_CURRENT_LIST_DIR}/DataTypes/")
add_fprime_subdirectory("${CMAKE_CURRENT_LIST_DIR}/GpioDriverPorts/")
add_fprime_subdirectory("${CMAKE_CURRENT_LIST_DIR}/SerialDriverPorts/")
add_fprime_subdirectory("${CMAKE_CURRENT_LIST_DIR}/SpiDriverPorts/")
add_fprime_subdirectory("${CMAKE_CURRENT_LIST_DIR}/I2cDriverPorts/")

# Components
add_fprime_subdirectory("${CMAKE_CURRENT_LIST_DIR}/BlockDriver/")
add_fprime_subdirectory("${CMAKE_CURRENT_LIST_DIR}/ByteStreamDriverModel/")
add_fprime_subdirectory("${CMAKE_CURRENT_LIST_DIR}/LinuxGpioDriver/")
add_fprime_subdirectory("${CMAKE_CURRENT_LIST_DIR}/LinuxSerialDriver/")
add_fprime_subdirectory("${CMAKE_CURRENT_LIST_DIR}/LinuxSpiDriver/")
add_fprime_subdirectory("${CMAKE_CURRENT_LIST_DIR}/LinuxI2cDriver/")
add_fprime_subdirectory("${CMAKE_CURRENT_LIST_DIR}/SocketIpDriver/")
