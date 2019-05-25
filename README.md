# EAP_proof_of_concept
Evil AP proof of concept

This is a demo of how one could spoof a WiFi network.

## Preps
### Window 1: interfaces

Use `iwconfig` to list available network interfaces. Choose one that is wireless (no kidding?!). To find the adapter your computer is using, you can get additionnal information with `ifconfig`. It is apparently often labeled as `UP BROADCAST RUNNING MULTICAST`.
Mine is `wlp2s0`.

