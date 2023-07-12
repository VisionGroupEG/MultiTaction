# MultiTaction
Contains new installation for MultiTaction screen, configurations, set up an application and references. 

## Installation

### Hardware Installation (1st time for 1 cell)
1. Connect the PC that has MultiTaction installed to the router via Wi-Fi or Ethernet
2. Connect the MT screen to the same router via Ethernet cable
3. Launch the screen and check its IP Address from the Auto DHCP panel and then switch it to **Manual** and make the IP address something out of the common range that can be given by the auto DHCP to the connected devices (i.e., 192.168.8.**225**)
4. Go to External source and navigate to `config.txt` file under: `C:\Users\multi\AppData\Roaming\MultiTouch` and update the `NetBridge` > `host = {ip address you added to the screen ie, 192.168.8.225}` 
5. Then **Save changes**
6. Start the **server** then the **MT Showcase App**

Note:
- For Point 1 and 2 above: 
    > Screen can be connected directly to the PC if the Ethernet is [Crossover not Straight-Through](https://www.bridgeheadit.com/straight-through-vs-crossover-cables-whats-the-difference/#:~:text=A%20crossover%20cable%20is%20also,each%20side%20of%20the%20cable.)


### config.txt example:
> [config.txt](./config.txt)
> 
> saved under: `C:\Users\multi\AppData\Roaming\MultiTouch`


### Touch Issues
if you still encounter an issue refer to [Touch Troubleshooting Guide.pdf](Touch%20Troubleshooting%20Guide.pdf)


### Full Setup Guide and Multi MT installations
[Setup Guide and MT Application](https://apps.multitaction.com/index.html)

This will require a username and password:
- `username: mustafaj@visiongroupeg.com`
- `password: Viviabdo12345`


### Designers and Operations
- [Showcase Tutorials YT Playlist](https://youtube.com/playlist?list=PLG3F5vZSbiasHO9JPCPJVNIuZl3algh_q)
- [Canvas Tutorials](https://youtu.be/XJpJiNGLN3M)
