# Irish ISP Fiber Settings (2025)
Fiber (FTTH) settings for Internet Service Providers in Ireland<br/>
The settings below eliminates the need to use the Router provided by your ISP and connect directly to your own network setup, in this case, a Ubiquiti Unifi setup. You can connect your UniFi router WAN port directlty to your ONT (typically Huawei in Ireland). This then connects to another box via fiber (known as anNetwork termination unit, or NTU).<br/>
<br/>
**Ubiquiti Unifi Configuration details**<br/> 
**Note**: Instructions based on UniFi Network 9 (2025)
* Login to UniFi Network (default URL is https://unifi<br/> 
* Click "settings" icon and then click on "internet"<br/>
* Click on "Primary (WAN1)"<br/>
* In "advanced" section, choose "manual"<br/>
* Tick "VLAN ID" and type in "10"<br/>
* Where PPPoE is required, go to the "IPv4 Connection" section, choose "PPPoE" and put in the "username" and "Password" details.<br/>
<br/>
<br/>

**Digiweb** <br/>
PPPoE Username: digiweb@siro.digiweb.ie<br/>
PPoe Password: digiweb<br/>
VLAN: 10<br/>
<br/>
**Eir** <br/>
VLAN: 10<br/>
<br/>

**Pure Telecom** <br/>
PPoE Username: puretelecom@puretel.ie<br/>
PPoE Password: broadband1<br/>
VLAN: 10<br/>
<br/>


**Sky Fiber** <br/>
PPPoE Username: anything@skydsl<br/>
PPoe Password: anything<br/>
VLAN: 10<br/>
<br/>
**Vodafone** <br/>
PPoE Username: vodafone@vodafone.ie<br/>
PPoE Password: broadband<br/>
VLAN: 10<br/>
**Note:** When I was with Vodafone previously, I had to use the serial number of the router as part of the username. EG  [ModemSerialNumber]@vfieftth.ie and password as "broadband", but may need to confirm again in future.
<br/>



