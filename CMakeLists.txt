set(COMPONENT_SRCDIRS "src" "src/AsyncMqttClient/Packets")
set(COMPONENT_ADD_INCLUDEDIRS "src" "src/AsyncMqttClient" "src/AsyncMqttClient/Packets")
set(COMPONENT_REQUIRES "arduino-esp32" "AsyncTCP")
register_component()