# ha_PZEM_004T_V3
Instruction how to use PZEM_004T_V3 without ESPHome and integrations. Only ha native Modbus codes.
with fllowing  four type connections.
培正PZEM 004T V3用电信息采集HA官方方案，需要集成，直接用HA的内置的Modbus模块
注意，本代码需要RS485的设备接一个转换器（例如串口服务器）来实现下面四种modbus（TCP，UDP，rtuovertcp，serial）之一来连接设备。

# Type of modbus.
one of these connection type is required for this yaml.
## tcp
TCP/IP connection with socket framer, used with Ethernet enabled devices.

## udp
UDP connection with socket framer, rarely used.

## rtuovertcp
TCP/IP connection with rtu framer, used when connection to modbus forwarders.

## serial
Serial connection with RTU framer, used with TTY port or USB rs485 converter.
