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
04:51 10:51 16:51 22:51
"000000000000FBDF90 560841 8C81FBDF90 E700 6C925F4A","snr":  0.25,"UTCtime":"2024-11-21T10:51:51Z"
"000000000000FBDF90 560841 8C81FBDF90 F100 6B4B7EA8","snr":  1.00,"UTCtime":"2024-11-23T18:03:14Z"
"000000000000FBDF90 560841 8C81FBDF90 7101 36BDEF54","snr":-10.25,"UTCtime":"2024-12-21T10:51:12Z"
"000000000000FBDF90 560841 8C81FBDF90 8901 16973CD0","snr":  7.75,"UTCtime":"2024-12-26T10:51:27Z"
"000000000000FBDF90 560841 8C81FBDF90 8D01 982BAD2B","snr":  6.75,"UTCtime":"2024-12-27T10:51:35Z"
"000000000000FBDF90 560841 8C81FBDF90 9101 56919BED","snr": 10.50,"UTCtime":"2024-12-28T10:51:17Z"
"000000000000FBDF90 560841 8C81FBDF90 9B01 0791ECD1","snr":  3.25,"UTCtime":"2024-12-30T10:51:35Z"
"000000000000FBDF90 560841 8C81FBDF90 9D01 B0ED1A0E","snr":- 0.75,"UTCtime":"2024-12-30T22:51:34Z"
"000000000000FBDF90 560841 8C81FBDF90 A901 C0AE9805","snr":  5.50,"UTCtime":"2025-01-02T16:51:47Z"
"000000000000FBDF90 560841 8C81FBDF90 AD01 A13B32E0","snr":  0.00,"UTCtime":"2025-01-03T04:51:37Z"
"000000000000FBDF90 560841 8C81FBDF90 AF01 2799AB6A","snr":  4.75,"UTCtime":"2025-01-03T16:51:51Z"
"000000000000FBDF90 560841 8C81FBDF90 B101 85984911","snr":- 1.75,"UTCtime":"2025-01-04T04:51:54Z"
"000000000000FBDF90 560841 8C81FBDF90 C301 BDF42200","snr":  0.50,"UTCtime":"2025-01-08T04:51:42Z"
```
```
"00535F36365F4152466E656741 3F51 0400 771334EF49C9","snr":- 9.50,"UTCtime":"2024-12-21T13:18:21Z"
"00535F36365F4152466E656741 3F51 0400 67FC754B0A92","snr":  1.50,"UTCtime":"2025-01-03T13:25:00Z"
"00535F36365F4152466E656741 3F51 0400 ACD2A278FA11","snr":-11.25,"UTCtime":"2025-01-05T13:27:01Z"
"00535F36365F4152466E656741 3F51 0400 08E356ECE2CF","snr":- 3.25,"UTCtime":"2025-01-06T13:23:11Z" 
"00535F36365F4152466E656741 3F51 0400 09E39A6D7F76","snr":- 3.50,"UTCtime":"2025-01-06T13:23:37Z"
"00535F36365F4152466E656741 3F51 0400 EF934221912E","snr":- 0.75,"UTCtime":"2025-01-10T13:26:06Z" 
"00535F36365F4152466E656741 3F51 0400 975E29DBD231","snr":- 4.75,"UTCtime":"2025-01-11T13:35:02Z"
"00535F36365F4152466E656741 3F51 0400 985E091CED82","snr":- 2.25,"UTCtime":"2025-01-11T13:35:48Z"
```

Birdz G3 start with the 8C:81:24:xx:xx:xx mac address

IEEE OUI give :
Address Prefix 90:df:fb (Big Endian)
Vendor / Company HOMERIDER SYSTEMS
Company Address 12 RUE REMORA GRADIGNAN GIRONDE FR 33170
Start Address 90:df:fb:00:00:00
End Address 90:df:fb:ff:ff:ff

