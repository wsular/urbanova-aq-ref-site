Datalogger Source Code
----------------------

The `.cr6` program file is loaded into datalogger memory and set for automatic
run on start-up.


## Sensor Configuration Details

Before using this program, sensors must be configured as described below.

### Teledyne T100U [SO<sub>2</sub>]

This device is integrated as an analog voltage measurement. Additionally, the
analyzer performs local data logging to an internal hard drive. Insofar as 
sampling configuration, the device should comply with EPA deployment guidelines.

* Analog interface
    * Reporting range: 0-100 ppb
    * Voltage range: 0-5 Vdc
* Onboard data acquisition system (DAS)
    * *leave default channels intact*
    * Channel: **1MIND**
    * Number of records: 45000
    * Trigger event: ATIMER
        * Parameter: CONC1 (PPB)
        * Sample mode: AVG
        * Precision: 1
        * Parameter: STABIL (PPB)
        * Sample mode: AVG
        * Precision: 2
    * Channel: **30MIND**
    * Number of records: 1500
    * Trigger event: ATIMER
        * Parameter: CONC1 (PPB)
        * Sample mode: AVG
        * Precision: 1
        * Parameter: STABIL (PPB)
        * Sample mode: AVG
        * Precision: 2

