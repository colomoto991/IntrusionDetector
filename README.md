# IntrusionDetector
author: scarlettomato 16,7,2022
It is the IRP of master in cranfield.
The objectives of this project are to detect intrusive traffic (refers to the packets in the transport layers)
This project contains 5 components:
1. The catcher of the packet, inplenmented by Scapy
2. The analyzer of the packet, used to extract required atrributes from the packet. Also implenmented by scapy.
3. The detector model (pretrained). Accepting the attributes from the analyzer.
4. The model trainer.
5. Traffic generator.


