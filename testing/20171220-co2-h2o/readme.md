# Pre-Urbanova Deployment Calibration

Licor LI-840A #4 (s/n HGA-3033)

Unit has been running for several days in PETB 417 sampling room air. Was 
previously involved in Indoor AQ study as sub-in for broken unit.

Connected to unit directly for this procedure instead of using logger program.
Gas sources were:

| Desc      | Cyl ref | Contents                     |
|-----------|---------|------------------------------|
| zero air  | JJ30248 | CO2 @ < 1 ppmv, balance air  |
| low CO2   | JB03183 | CO2 @ 360 ppmv +/-1% NIST, CH4 @ 1527 ppbv +/-1% NIST, balance UP air |
| high CO2  | JA01944 | CO2 @ 1225 ppmv +/-1% NIST, CH4 @ 4.07 ppmv +/-1% NIST, balance UP air |
| low H2O   | LI-610 s/n DPG1161B | set to 3.00*C |
| high H2O  | LI-610 s/n DPG1161B | set to 21.00*C (room is 23*C) |

*Note: choice for H2O span based on paragraph **Considerations for performing
a secondary span:** on page 3-29 of LI-840A user manual (rev 5/15).*

Previous service dates reported by analyzer:

* CO2 zero: neglected to record
* H2O zero: neglected to record
* CO2 span: 2017-08-27 at 13:27
* H2O span: 2017-08-27 at 14:17
* CO2 span2: 2017-08-27 at 13:27
* H2O span2: 2017-08-27 at 14:17


> TODO retrieve pictures of experimental setup from tablet


### Notes

```
15:19   Begin flowing zero air... increase delivery flow at 15:20
15:26   Add a rotameter to overflow line for improved flow stability
15:31   Initiate CO2 & H2O zero calibrations on analyzer... OK
        --> at least 15min flush out H2O? yes
15:33   Swapped zero tank over to high CO2 span... initiating flow
15:49   Readjust pressure... was still overflowing OK
15:50   (turn on dewpoint geneator to warm-up)
15:53   Initiate CO2 Span @ 1225 ppm... switch tanks over once finished
15:56   Now flowing low span CO2 gas
16:13   (begin flowing H2O @ 3*C from dewpoint generator to condition gas line
16:14   Initiate CO2 span 2 @ 360 ppm... OK
16:17   Replaced PFA gas inlet with Bevaline H2O inlet from dpgen
16:18   ... Observe dpgen cooler is not turned on... turn it on

17:00   Halt data log... still waiting to get to dewpoint generator setup. Is
        flowing 3.00*C-H2O at ~1.5 LPM with verified overflow

17:35   Begin data collection again. Analyzer reports 2.85*C for 3.00*C stream.
17:42   Initiate H2O span @ 3.00*C...
17;44   Adjust dpgen setpoint to 21.00*C
18:08   Reporting 21.05*C... initiate H2O span 2 @ 21.00*C
18:09   Reconnect inlet to rack manifold = room air
18:14   Halt data acquisition
```


