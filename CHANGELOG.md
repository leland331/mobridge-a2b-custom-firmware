# Changelog

## LB-06 / 2.11.14

First public release. Based on stock 2.11.8:

- Keeps amps on while the radio module is awake or audio is on, fixing a parked wake fault that left audio silent.
- Prevents amp remote from cycling off and on at ignition-on.
- Keeps the unit powered for about five seconds after dropping amp remote during shutdown.
- Delays stopping the internal DSP until the amps have been off for four seconds.
- Briefly mutes DSP startup at ignition-on when the amps are already on.

[Release notes and checksums](release-notes/LB-06.md)
