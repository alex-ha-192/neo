This isn't anything about the force required to push or the size or weight, it's just in terms of integration with the central unit.

=> Needs to work in either bus or star topologies
==> So therefore, it needs two ports (one towards hub and one towards the next buzzer in the chain), preferably something easily swappable e.g. XLR

=> If we're using RS485 or something like that, we'd need at least 4 contacts, so either XLR4 or XLR5 is probably best
==> ATTiny (insert model number here) + RS485 rx/tx is probably the best shout

People seem to prefer a larger boxy buzzer to Kitsune size
One male, one female port

Let's do a BoM real quick:

LED: negligible
2 PCBs: About a pound?
Keyboard switch: like 50p
3D printed case: I can probably get free printing off Imperial somehow
2x XLR4/5 connector: £1.16 (https://cpc.farnell.com/cliff-electronic-components/fc61945/xlr-plug-4p-p-mount-metal-black/dp/CN27138) + £2.60 (https://cpc.farnell.com/pro-signal/psg08607/socket-xlr-chassis-4p/dp/CN21151) = 3.76£
ATTiny something or other: 50p for a 412 on DigiKey
RS485 tx/rx (This weird thing, the HW-519 apparently: https://www.aliexpress.com/w/wholesale-ttl-rs485-auto-flow-control-module.html?spm=a2g0o.productlist.auto_suggest.2.71b541b1fdGYJb): also about 50p

So just under £6.50 per buzzer => £52 for a set of 8

Possibly cheaper to use GX12-4 aviation connectors? Worth a look
