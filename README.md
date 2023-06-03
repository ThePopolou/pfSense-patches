# pfSense-patches
Misc patches to customise the firewall OS. **Please use at your own risk.**

## Available Patches
**`vpn_openvpn_export_p2p.patch`** - _Alters the Client Export package to allow for exporting Peer-to-Peer connections on a OpenVPN server that is configured for use as Remote Access only._ Good practice (or at least that advised by the package devs) is that you have a seperate OVPN instance for each mode. All rather unecessary and cumbersome if you only have a handful of users/devices.
