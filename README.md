# SMRoutes by SmartModules - A phpVMS Module Factory
SMRoutes was developed to automatically generate routes based on the capacity of each aircraft, such as: range, cruise, minimum runway length, among others. The module uses information from the phpvms_airports and phpvms_aircrafts tables, but is not limited to them, as the module uses its own tables to obtain other information.

***************************************
NOTE: This module has been tested with the phpvms_5.5.2.72-master version by ProAvia (https://github.com/ProAviaAZ)
****************************************

# How does its work?
The module uses information from the phpvms_airports and phpvms_aircrafts tables. However, the module does not make any changes to the original tables in phpVMS.

The generated routes are recorded in the phpvms_schedules table after they are previously constructed.

The current version has two options for creating routes: Roundtrip and Air Bridge.
