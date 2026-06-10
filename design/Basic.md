Probably have an star topology like the Kitsunes

Can restrict to only a [[Button]], LED, [[Connector]] on each individual buzzer, with [[Microcontroller]], transistors, etc. etc. in a central control unit

BoM 1:
Control board:

| Part                | Qty (assuming 8 buzzers) | Price    | Price * qty    |
| ------------------- | ------------------------ | -------- | -------------- |
| ESP32-S3 dev board  | 1                        | 10.60    | 10.60          |
| BC547B transistor   | 8                        | Fuck all | Fuck all * 8   |
| 100nF cap           | 8                        | Fuck all | Fuck all * 8   |
| XLR connector       | 8                        | 1.29     | 10.32          |
| Resistors           | IDK                      | Fuck all | Fuck all * IDK |
| PCB                 | 1                        | 0.94     | 0.94           |
| Active/piezo buzzer | 1                        | 4.27     | 4.27           |
| LEDs                | 8                        | Fuck all | Fuck all * 8   |
Total for control board => 26.13 (round up to £30)

Buzzer:

| Part              | Qty/buzzer | Price    | Price * qty |
| ----------------- | ---------- | -------- | ----------- |
| Keyboard switch   | 1          | 0.40     | 0.40        |
| LED               | 1          | Fuck all | Fuck all    |
| Maybe a resistor? | 1          | Fuck all | Fuck all    |
| PCB               | 2          | 0.94     | 1.86        |
| XLR connector     | 1          | 1.29     | 1.29        |
| XLR cable (2m)    | 1          | 2.40     | 2.40        |
Total per buzzer => 5.95 => £50ish for the set

Approximate BoM cost => Around £80