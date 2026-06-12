# Control unit
- Based around either a Raspberry Pi Pico or an ESP32
- Features a RESET button and 4 LEDs for each team
- One DMX/XLR5 port on each side for buzzer daisy chain

# Buzzers
- Based around an ATTiny or similar
- One male and one female DMX/XLR5 port on each side
- Features a button and an LED

# Communication
- Enumeration takes place over I2C/UART/Serial or something really basic - needs to run on RESET (and therefore RESET must be pressed before a game - initialise the LEDs to ON on the control unit)
- Switch to RS485 after enumeration for minimal latency
- Termination resistor in control unit only, hope for the best

# Buttons
- Use mechanical keyboard switches with minimal capacitor debounce to reduce latency
- Either use standard keycaps or 3D print "buzzer button"-style caps

# Parts List
- DMX/XLR5: https://cpc.farnell.com/cliff-electronic-components/fc61955/xlr-plug-5-pole-panel-mount-black/dp/CN22651, https://cpc.farnell.com/cliff-electronic-components/fc61950/xlr-socket-5-pole-p-mount-latch/dp/CN22650, https://cpc.farnell.com/pulse/pls00408/lead-xlr-dmx-5p-2pair-0-5m/dp/AV22551
- RS485 board: https://www.aliexpress.com/w/wholesale-ttl-rs485-auto-flow-control-module.html?spm=a2g0o.productlist.auto_suggest.2.71b541b1fdGYJb