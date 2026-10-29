# Changelog

## Beta

### LB-RC1 / 2.12.0
LB-06 plus:
- **Rear Chimes:** park-assist and cross-traffic tones can be routed to rear outputs, with their own level.
- **Live meters for all 12 outputs** (stock firmware reports only 1-8).

Rear Chimes routing needs an app that supports it; the official app may clear it when it saves routing.
[Release notes and checksums](release-notes/LB-RC1.md)

## Stable

### LB-06 / 2.11.14
First public release. Based on stock 2.11.8:
- Keeps amps on while the radio module is awake or audio is on, fixing a parked wake fault that left audio silent.
- Prevents amp remote from cycling off and on at ignition-on.
- Keeps the unit powered for about five seconds after dropping amp remote during shutdown.
- Delays stopping the internal DSP until the amps have been off for four seconds.
- Briefly mutes DSP startup at ignition-on when the amps are already on.

[Release notes and checksums](release-notes/LB-06.md)
