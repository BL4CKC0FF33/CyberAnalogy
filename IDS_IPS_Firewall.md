# IDS vs IPS vs Firewall

### First, what are they?  
* **IDS (Intrusion Detection System)**: is a system/device (software/hardware) in the network to detect malicious activity, for example: if there was a port scanner running the IDS will be triggered, it will not stop it, but it will log it.

* **IPS (Intrusion Prevention System)**: is a system system/device (software/hardware) in the network to prevent malicious activity, for example: it can drop the malicious packet if spotted (based on the config). 

* **Firewall**: is a system/device (software/hardware)  in the network to block connections from/to the network, for example: if a user wanted to connect to a server he/she will be able to connect via the open ports that the firewall specifies. 

![Vs(1)](https://user-images.githubusercontent.com/69141453/116835365-f92e8c00-ab76-11eb-8bb8-ad8b6e2b939f.png)

The above diagram shows an anaology of the 3 technologies.

The **IDS** acts as a camera, it can only watch and record (log) and it cant stop anyone from coming in.
As for the **IPS**, it can act like a door, the IPS can close the door if necessary.
And finally the **firewall** is the lock on the doors.

Every network tapology differs based on the customer's needs but this is the basics.
the **firewall** sits behinds the router and then the **IDS** and/or **IPS**.

![VS-part2](https://user-images.githubusercontent.com/69141453/116952787-60fcd980-ac40-11eb-8503-1fc81040c0f4.png)
