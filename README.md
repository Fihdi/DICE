# 6hp Sample and Hold / Random voltage generator

![](https://github.com/Fihdi/DICE/blob/main/DICE-Front.png?raw=true)

DICE contains a white noise generator, sample and hold and a comparator. This 6hp module creates various random voltages and gates, bringing variety and unpredictability into your patches. 


# Applications

- Random voltage generator
- Random gate generator
- Slew rate limiter
- Track and hold
- White noise generator
- Burst generator

# Jumpers
Two jumpers on the back of the module allow the COMP output to be configured:
- **Jumper in the ON position:** A trigger from TRG is always routed to the COMP output. This ensures an on-time trigger when using the COMP output as a burst generator.
- **Jumper in the OFF position**: The trigger from TRG is not routed to the COMP output.
- **Jumper in the AND position:** The COMP output is only active while a gate signal is present at the TRG input.
- **Jumper not in the AND position:** COMP outputs HIGH or LOW signals regardless of the TRG input.



