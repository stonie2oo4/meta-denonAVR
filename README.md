## DENON DRIVER FOR NEEO-META OVER HTTP
This package is still under development, but has been tested for a number of buttons on AVR-4500.

# Contents
This package consists of both a NEEO-MEA devicedriver.

NodeRED files not longer needed.

Zone2+3 not implemented at the moment.

# Connectiviy
 The "meta" on the Denon AVR3808 (maybe this applies to all Denon-devices) will only connect successfully to your Denon if no other connection is running. Multiple connections don't seem to be supported by the Denon firmware. 
 
# POWER ON and OFF
This package can power on your Denon over Telnet if the Denon is keeping the network connection OPEN.
The POWER OFF command will put the Denon in standby mode, so it can be woken up by Telnet-commands.  

# Autodiscovery 
Not supported. IP must registerd at the start of the driver.

# Issues
Slider gives no response.
Seeminly the listener doesn't work right in this driver.
