
	/===============================\
	| EPKK_APP - APPROACH CONTROLLER|
	|				|
	|POLISH VACC ATC TRAINING CENTER|
	\===============================/
	 
________________________________________________

INITIALPSEUDOPILOT:EPKK_X_APP

PSEUDOATC:
- EPWW_ALL_CTR
- EPKK_TWR
- EPKT_TWR

SWEATBOX WITH MENTOR:
-  MENTOR - EPKK_X_APP
- TRAINEE - EPKK_APP

SWEATBOX TRAINEE ONLY:
- TRAINEE - EPKK_X_APP

_________________________________________________

SCENARIO DETAILS:
- DEPARTURE AND ARRIVALS TO EPKK, EPKT and EPRZ
- DEPARTURES READY FOR MANUAL TAKEOFF NEAR RUNWAY
_________________________________________________

A DERIVATIVE OF THE ORIGINAL EPKK 25/EPKT 26 SCENARIOS PREPARED BY Bohdan/1651370 DURING HIS S3 TRAINING IN 2024/25 :)

EPKK_APP_25_26_27_group_flight.txt
* a scenario incorporating two more demanding tasks at the same time - managing a group flight to EPKK (from LKAA) and traffic to/from EPWA
* the timing of departures is crucial:
    - FDB1788 from EPKK should ideally depart when the group flight is on downwind
    - departures to EPWA should coincide with traffic from there getting close to KUKAM
    - MGH874 should depart to coincide with ENT72EN and RYS7110 coming in via BAVOK
* in some cases, there are duplicate squawks - this is deliberate to enforce remembering about proper identification even with higher workload

_________________________________________________
