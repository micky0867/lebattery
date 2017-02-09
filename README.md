# lebattery
LE-Bluetooth battery measurement for FHEM


You will need FHEM (http://fhem.de) and lepresenced (https://github.com/mhop/fhem-mirror/blob/master/fhem/contrib/PRESENCE/lepresenced) for this.

Reads battery values from all le-bluetooth devices configured in FHEM and writes them to a given attribute in FHEM.

Supports both, Gigaset and Nut devices.

Gigaset devices have public addresses (switch -t public)

NUT devices have static random addresses (switch -t random)

Needs FHEM, lepresenced, bluez, gatttool and socat. Depending on your distribution, also gawk is needed.

Options:

-Update all LE-tags defined in FHEM:<br>
./lebattery -v

-Update only given LE-tags in FHEM:<br>
./lebattery -v tagname1 tagname2 ....

See also http://www.fhemwiki.de/wiki/Anwesenheitserkennung
