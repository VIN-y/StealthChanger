# Gantry x/y endstops for Voron

This mod is a remixing the endstop carrier from [MrTeliP](https://www.printables.com/model/325765-voron-24r2-pg7-cable-gland-and-endstop) (on Printables)

### Pupose

It move the X and Y endstop switches to a single assembly, which attached to the stock Voron A(Y) motor mount. 

### Assembly

This assembly is held in place by replacing the original two M3x30mm bolts with two M3x35mm bolts, which passed through the holes on the assembly (See the **Images** folder).

### How it works

This configuration works by using the `[force_move]` and `[homing_override]` function in Klipper config to create make sure that the Y-axis is homed before the X-axis. (see the homing.cfg)
