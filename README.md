# Volumio_AK4490
AK4490 Plugin for volumio2. This plugin control AK4490 chip by i2c.
User must connect i2c pins between raspberry pi and es9018k2m DAC. I2C lines connections: 
    SCL is on pin 3 and SDA is on pin 4 of the DAC
supported platform: Raspberry Pi
supported board: 

supported functions
select digital filter(fast/slow rolloff, IIR) and de-emphasis filter
i2s/DSD DPLL(Digital Phase Locked Loop) Jitter Reduction
volume, mute control
adjust balance and switch left/right channel
