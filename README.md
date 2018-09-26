# PainPreDix
PainPreDix is a sketch for the watchX that adds pain flare prediction to a digital watch.
This version of the sketch is fully functional as a 12-hour watch, which is a nice
coincidence since the watch will run for at least 12 hours between recharges. After
that, it's pretty much a crap-shoot! If the battery runs down to the level that the 
watch stops running, you'll need to edit the sketch (in the setup section) to set
time again.

Pain prediction is based on environmental conditions that may be measured by the 
BME280, and these include temperature, humidity, and atmospheric pressure. Of these
three, it's pretty clear that temperature may easily be affected by proximity to
the wearer's body. Humidity may be affected as well, and of course both humidity 
and temperature may be influenced significantly by the immediate location (such as 
in a sauna, bathroom, kitchen, etc.). Atmospheric pressure is less likely to be an
issue unless the wearer is at an altitude significantly different from sea level, or
if the wearer is in an artificially pressurized environment. All of these things 
must be understood to know how much credence to give to the pain risk calculation.


