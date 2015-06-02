cpu-frequency
-------------

*cpu-frequency* is a simple application that appears in the system tray, and displays CPU frequency scaling, as a bargraph with a bar for each CPU core

The *pstate* power scaling driver selects the 

(FWIW, the default *powersave* governer seems to do a good job in a desktop environment)

nice docs on the [Arch wiki](https://wiki.archlinux.org/index.php/CPU_frequency_scaling)


Anthony Kirby - [anthony@anthony.org](mailto:anthony@anthony.org), June 2015


TODO
----

* test on multi-CPU (as well as just multi-core)
* test with a wider range of CPU counts & types
* handle system tray sizes & re-sizing
* RPM / .deb packaging
* test with CPUs with different range of min/max
* more documentation, manpage, "-v" option etc

