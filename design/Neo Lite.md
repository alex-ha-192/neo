# Control Unit
- RESET, player LEDs
- Based around an MCU (probably an ESP32 for cost)
- Features all active components (mostly the LED drive transistors)
- Likely 8-10 player ports for a star topology

# Buzzers
- Features a button, LED, and one connector

# Communication
- Simple high-low buzzer lines to MCU
- Separate LED drive lines after MCU processes lockouts

# Buttons
- Use mechanical keyboard switches with minimal capacitor debounce to reduce latency
- Either use standard keycaps or 3D print "buzzer button"-style caps

# Connectors
- Likely XLR(3)