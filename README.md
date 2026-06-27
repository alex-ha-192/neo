# Neo
The Neo buzzer system is an open-source, hopefully reliable, and hopefully affordable line of quiz lockout buzzers. It also does not currently exist. This is a rather significant flaw, though one I'm working to repair.

## Progress
### Classic v1
- [x] Finalise design concepts
- [ ] Prototype
- [x] Source parts
- [ ] PCB design
- [ ] 3D printed case design
- [ ] Order and initial testing
- [ ] Real-world testing
- [ ] Release

### Lite v1
- [x] Finalise design concepts
- [ ] Prototype
- [ ] Source parts
- [ ] PCB design
- [ ] 3D printed case design
- [ ] Order and initial testing
- [ ] Real-world testing
- [ ] Release

### Footprints
- [x] XLR5 Male (has now arrived at my house)
- [x] XLR5 Female (has now arrived at my house)
- [ ] XLR3 Male
- [ ] XLR3 Female
- [ ] HW-0519

### PCBs (started/schematics)
- [x] Main buzzer board - Classic
- [x] Main control board - Classic
- [x] LED board - Classic
- [x] Button/LED assembly - Classic
- [x] Male connector assembly - Classic
- [x] Female connector assembly - Classic
- [ ] Buzzer - Lite
- [ ] Control board - Lite
- [ ] Male connector assembly - Lite
- [ ] Female connector assembly - Lite

### PCBs (completed/routing)
- [ ] Main buzzer board - Classic
- [ ] Main control board - Classic
- [ ] LED board - Classic
- [ ] Button/LED assembly - Classic
- [ ] Male connector assembly - Classic
- [ ] Female connector assembly - Classic
- [ ] Buzzer - Lite
- [ ] Control board - Lite
- [ ] Male connector assembly - Lite
- [ ] Female connector assembly - Lite

### CAD models
- [ ] Buzzer box - Classic
- [ ] Control unit - Classic
- [ ] Male connector assembly - Classic
- [ ] Female connector assembly - Classic
- [ ] Buzzer box - Lite
- [ ] Control unit - Lite
- [ ] Male connector assembly - Lite
- [ ] Female connector assembly - Lite

## Pricing
I'm trying to be cost-conscious while designing these buzzers, but I'm not planning on imminently selling any or distributing them beyond Imperial until they're both finished and well-tested. If you need a buzzer set now, I'll point you to buying a [Kitsune system](https://github.com/Amekyras/kitsune) from [Aisling Skeet](https://github.com/Amekyras); they're a solid set of buzzers and they've been tested at quite a few competitive events. If you want a pricing estimate, it's probably whatever I say it is at the moment plus a bit on top because this keeps getting more expensive with every revision.

Just a quick note as well, this is an open-source project and, as a result, you can do whatever you'd like as per the [licence](LICENCE), but if you want to make your own buzzers, please don't sell them? Obviously I neither can nor will try and stop you, but these haven't been particularly cheap to work on, even though as I write this I haven't shipped out any PCBs yet - parts are expensive! I'd love it if anyone who wants to improve them does that though, either on this repository or on your own fork.

## Features (planned, WIP)

### Classic v1.0
- Daisy-chain as many buzzers per side as you could ever reasonably want
- USB-C connection with data for potential [BuzzIn.live](https://buzzin.live) support or generic input
- Low/fair latency
- Static discharge protection and industrial signalling for reliability
- At-home reflashable central unit firmware for customisation/DIY firmware upgrades
- Open source!
