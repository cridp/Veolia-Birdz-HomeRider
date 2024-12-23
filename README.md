# Veolia-Birdz-Kamstrup-HomeRider

LoRaWAN®: LoRaWAN 1.0.4 class A
1.10 Is the device already working on a public LoRaWAN network. No
1.17 Is the payload structure available for decoding? No
1.18 Is there a decode-API available ? No
1.19 Is the firmware upgradeable and how? Yes With the B-TOOLZUP app (available on the Google Play store)
2.1 DevEUI Range (IEEE Compliance): From : 90 DF FB 00 00 2E C0 00 To : Currently indetermined
2.12 Is Activation Type OTAA the default: Yes
2.13 For OTAA, is AppKey unique for each device? Yes
2.17 Is the device doing a periodical rejoin? (only for OTAA): No
2.18 Is the first join request sent on SF12? Yes
2.19 On what SF and power setting is the first uplink (after join procedure) done? SF12
2.20 Are you doing periodically reset of Uplink frame counter? No
2.21 If LoRaWAN 1.0.x, DevNonce behaviour : Monotonically increasing never-wrapping counter
2.31 LoRaWAN Stack Type (optional): Proprietary- Other, name it: Stack by Birdz
2.33 LoRa Radio Hardware (optional): Proprietary: SX chip used: SX1262
2.34 Multicast support (optional): No




First Attempt with Kamstrup FlowIQ 2200 with Birdz G3 module
"frequency":868100000,"spreadingfactor":9,"signalbandwidth":125000,"codingrate":6,"preamblelength":8,"syncword":"0x34","enablecrc":false,"invertiq":false

```
000000000000 FBDF90 470B41 8C81 FBDF90 9100 2BAAE5AF
000000000000 FBDF90 50A041 8C81 FBDF90 4F00 7E3CC2B0
000000000000 FBDF90 2EC741 8C81 FBDF90 4F00 1D4133DE
000000000000 FBDF90 2FC741 8C81 FBDF90 4F00 7919E9DF
000000000000 FBDF90 400B41 8C81 FBDF90 B300 9ADA63D7
000000000000 FBDF90 6B0541 8C81 FBDF90 0900 BCBC0BA3
000000000000 FBDF90 560841 8C81 FBDF90 A500 B6E30EE5
000000000000 FBDF90 970D3F 8C81 FBDF90 0902 BFBB0194
000000000000 FBDF90 970D3F 8C81 FBDF90 1902 32390348
000000000000 FBDF90 632142 8C81 FBDF90 A300 03A7E1A0
000000000000 FBDF90 632142 8C81 FBDF90 A500 2D32CB4E
```

Birdz G3 start with the 8C:81:24:xx:xx:xx mac address

IEEE OUI give :
Address Prefix 90:df:fb (Big Endian)
Vendor / Company HOMERIDER SYSTEMS
Company Address 12 RUE REMORA GRADIGNAN GIRONDE FR 33170
Start Address 90:df:fb:00:00:00
End Address 90:df:fb:ff:ff:ff

