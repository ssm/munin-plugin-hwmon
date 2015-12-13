# Munin plugin for hwmon #

Munin plugin for hwmon sensors on Linux.

This plugin graphs sensors using the sysfs interface.  For
documentation, see
https://www.kernel.org/doc/Documentation/hwmon/sysfs-interface

This plugin will graph voltages, fans, temperatures, currents, power,
energy and humidity sensors.

Limits for warnings and criticals are read from the limits configured
in hwmon (max, min, lcrit, crit).
