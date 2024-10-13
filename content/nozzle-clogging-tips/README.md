# PLA/PETG Heat Creep Clogging

## The Issue

This is unfortunately a semi-common issue that is affecting the first batch of Qidi Plus 4 printers.
This issue mostly affects PLA, and sometimes affects PETG as well.

The stock nozzle has a stainless-steel heatbreak between the heating element and the heatsink.

The stock heatsink cooling fan is not mounted directly onto the hotend heatsink, and so it can receive insufficient cooling to prevent heat-creep clogging when printing models with high amounts of retraction.

## The Fix(es)

The ceramic heatbreak nozzles appear to work, while the other fixes here will help to minimise, but not completely fix, the chance of clogging.

There have been no reports on the Qidi Discord server of people seeing clogging after installing the ceramic heat-break nozzle, along with installing the duct and better fan.

- Install a nozzle from Qidi that has the ceramic heatbreak.  eg. [Ceramic Heatbreak Nozzle](https://qidi3d.com/products/plus-4-bimetal-nozzles-2pcs).  These can be easily identified by the white heatbreak section between the upper and lower portions of the nozzle, whereas the stainless steel heatbreaks are silvery in appearance.
- Print (in ABS or ASA) and install the heatsink duct model from here: https://www.thingiverse.com/thing:6782612  This model helps to better direct the cooling fan's airflow over the heatsink.
- Install a stronger heatsink cooling fan.  I recommend the GDSTime GDA30105F fans, which can be purchased from this [US Store](https://west3d.com/products/gdstime-dc-24v-30x30x10-axial-fan-24v-gda30105f-dual-ball-bearing-1200rpm-1w-06a-xh2-54), or from this [EU Store](https://www.hotend.eu/p/gdstime-axial-fan-sleeve-3010-24v)
- Raise the nozzle temperature by 5-10C.  This can sometimes resolve the heatcreep clogging as it keeps the filament within the heatbreak molten for longer between retraction events.

