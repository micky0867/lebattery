# lebattery
LE-Bluetooth battery measurement for FHEM


You will need FHEM (http://fhem.de) and lepresenced (https://github.com/mhop/fhem-mirror/blob/master/fhem/contrib/PRESENCE/lepresenced) for this.

Reads battery values from all le-bluetooth devices configured in FHEM and writes them to a given attribute in FHEM.

Needs FHEM, lepresenced, bluez, gatttool and socat.

