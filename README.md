# USB Power Injector

The USB Power Injector allows a convenient way to power up USB 2.0 devices from a lab power supply, while still allowing data transfer from the device to the host. 

## The problem

When powering devices from a standard USB 2.0 port, either from a PC or from a standard USB hub, you never have the niceties that an adjustable lab style power supply has. 
During development that means you can’t set precise voltage and current limits. In the best case scenario, that means you can’t test under/over voltage protections. 
In the worst case, you run excessive current trough your device and you don’t even know that’s happened.
USB hubs tend to have overcurrent protection, but most don’t send the overcurrent event to the operating system. 
That can cause confusion and loss of time for a hardware engineer during development or to testing personnel during production.  
