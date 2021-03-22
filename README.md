# que3
Modbus is a data communications protocol originally published by modicon.
Modbus protocol uses character serial communication. The modbus protocol is defined as a master/slave protocol,meaning a device operating as a master will poll one or more devices operating as a slave. This means a slave device cannot volunteer information,it must wait to be asked for it. The master will write data to a slave device’s registers. A register address reference is always in the context of the slave’s registers.
   The most commonly used form of modbus protocol is RTU over RS-485. Modbus RTU is simple serial protocol that can be transmitted through UART technology. Data is transmitted in 8-bit bytes,one bit at a time, at baud rates ranging from 1200 bits per second to 115200 bits per second.The majority of Modbus RTU devices support speeds up to 38400 bits per second.
   The types of registers in modbus devices include:
1) Coll (Discrete output).
2) Discrete input.
3) Input Register.
4) Holding register.
