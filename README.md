 PROJECT  : Bluetooth Home Automation
  MCU      : LPC2129 (ARM7TDMI-S)
  CRYSTAL  : 12 MHz
  BAUD     : 9600 (HC-05 Bluetooth Module)
  
  PIN MAP:
    P0.0  -->  UART0 TXD  (to HC-05 RXD)
    P0.1  -->  UART0 RXD  (from HC-05 TXD)
    P1.16 -->  Relay 1    (Light 1)
    P1.17 -->  Relay 2    (Light 2)
    P1.18 -->  Relay 3    (Fan 1)
    P1.19 -->  Relay 4    (Fan 2)

  COMMANDS (send from phone BT app):
    A = Light1 ON   |  a = Light1 OFF
    B = Light2 ON   |  b = Light2 OFF
    C = Fan1 ON     |  c = Fan1 OFF
    D = Fan2 ON     |  d = Fan2 OFF
    E = ALL ON      |  e = ALL OFF
