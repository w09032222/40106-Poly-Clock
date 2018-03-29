# 40106-Poly-Clock

A poly-clock module with inverted output and a swtich to choose between 3 sync modes.

mode 1:sync mode.
In this mode, two clocks will be run in the same speed but in different division.

mode 2:split mode.
In this mode, two clocks will not sync with each other.

mode 3:off-beat mode.
In this mode, clock2 will only start running when the clock1's signal is low (both of the clock are in 50% duty cycle).
