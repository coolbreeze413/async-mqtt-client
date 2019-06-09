set(COMPONENT_SRCDIRS "src" "src/AsyncMqttClient/Packets")
set(COMPONENT_ADD_INCLUDEDIRS "src" "src/AsyncMqttClient" "src/AsyncMqttClient/Packets")
set(COMPONENT_REQUIRES "arduino-esp32" "espidf_c_arduino_AsyncTCP")
register_component()