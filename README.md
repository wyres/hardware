# hardware
Wyres boards hardware information

# W_PROTO

These were the initial prototype boards used for testing. They were not CE or RF certified and classed only as experimental.

# W_BASE_V2

These were the production boards, with CE and RF certification (EU).

2 versions were produced, revB and revC. The rear silkscreen indicates the version. There are 2 main differences going to revC: 

 - the slide power switch has been removed and a hall effect switch added to reset the MCU (no firmware impact)
 
 - the RF chain tx/rx switch was updated and the antenna matching was improved meaning the overall LoRa RF performence is better on the revC.

Note that for the RF switch change the firmware must be aware of its board version as the tx/rx selection gpio's polarity was inversed. In all other respects the revB/C are identical.

