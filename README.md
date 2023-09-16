# ha_PZEM_004T_V3
Instruction how to use PZEM_004T_V3 without ESPHome and integrations. Only ha native Modbus codes.
with fllowing  four type connections.

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
