
# RadioCapture.com KerberosSDR 4x Autocal

#### Current (only) production run: v1.0 2021.09.a

## What is it?

This repo contains data for the RadioCapture.com KerberosSDR 4x Autocal board. It connects internally in the KerberosSDR to eliminate the need to disconnect and reconnect antennas during calibration, and provides a 50 ohm load for the noise source to output into. It is connected in between the existing antenna inputs and connections are soldered for 3.3v, ground, and control voltage which is provided via the noise source LED. 

They are intended to allow unattended operation of KerberosSDR's direction finding capabilities.

The Xinluda rf switch chip used has 0.3-0.5 dB insertion loss and 20-25 dB port to port isolation, so you may want to daisy chain two if you are in a noisy environment.

## Can I buy one?

NOTE: Install instructions and testing results to demonstrate the kerberos still works right are in-progress.


Yes I only needed 10 but I couldn't buy less than 5 PCBs worth, so I have a lot of spares.

I'm not totally setup yet, if you just want a board they are currently $10 each. Price includes shipping via USPS First class mail in an ESD safe bag. 


## Installation guide


IMPORTANT: These boards do NOT have independent anti-static protection so you MUST use a proper anti-static wrist strap that grounds you when handling and installing them. Please do not open the ESD bag unless you are properly grounded.

Coming soon?


## Credits

Original design by UB9MAS: https://oshwlab.com/ub9mas/4x-antenna-switcher-pe4259
Updated design by Akhil Sam (via Upwork).
Manufactured by RadioCapture.com / Matt Mills in Shenzen, China (JLCPCB)

If you have the need to switch 4 antenna inputs between an output and a 50 ohm load, that's all it does.

## Falstad CircuitJS Simulation:

https://tinyurl.com/yedr5w78


