# Supported Models

Any hardware supporting SSE4.1 CPU and 64-Bit firmware work on this patcher. To check your hardware model, run the below command on the applicable machine:

```bash
system_profiler SPHardwareDataType | grep 'Model Identifier'
```

The below table will list all supported and unsupported functions of the patcher currently:

* [MacBook](#macbook)
* [MacBook Air](#macbook-air)
* [MacBook Pro](#macbook-pro)
* [Mac mini](#mac-mini)
* [iMac](#imac)
* [Mac Pro](#mac-pro)
* [Xserve](#xserve)

### MacBook

| SMBIOS | Year | Supported | Comment |
| :--- | :--- | :--- | :--- |
| MacBook1,1 | Mid-2006 | <span style="color:red"> NO </span>  | 32-Bit CPU limitation |
| MacBook2,1 | Late 2006 | ^^ | 32-Bit Firmware limitation |
| MacBook3,1 | Late 2007 | ^^ | ^^ |
| MacBook4,1 | Early 2008 | ^^ | ^^ |
| MacBook5,1 | Late 2008 | <span style="color:#30BCD5"> YES </span> | - No GPU Acceleration in Big Sur<br/>- No AppleHDA(Audio) Patching implemented(yet) |
| MacBook5,2 | Early 2009 | ^^ | ^^ |
| MacBook6,1 | Late 2009 | ^^ | ^^ |
| MacBook7,1 | Mid-2010 | ^^ | ^^ |

### MacBook Air

| SMBIOS | Year | Supported | Comment |
| :--- | :--- | :--- | :--- |
| MacBookAir1,1 | Early 2008 | <span style="color:red"> NO </span> | Requires SSE4.1 CPU |
| MacBookAir2,1 | Late 2008 |<span style="color:#30BCD5"> YES </span> | - No GPU Acceleration in Big Sur<br/>- No AppleHDA(Audio) Patching implemented(yet)<br/>- No Wifi Patches implemented(yet) |
| MacBookAir3,1 | Late 2010 | ^^ | - No GPU Acceleration in Big Sur<br/>- No AppleHDA(Audio) Patching implemented(yet) |
| MacBookAir3,2 | ^^ | ^^ | ^^ |
| MacBookAir4,1 | Mid-2011 | ^^ | ^^ |
| MacBookAir4,2 | ^^ | ^^ | ^^ |
| MacBookAir5,1 | Mid-2012 |^^ | <span style="color:green"> Everything is supported</span> |
| MacBookAir5,2 | ^^ | ^^ | ^^ |

### MacBook Pro

| SMBIOS | Year | Supported | Comment |
| :--- | :--- | :--- | :--- |
| MacBookPro1,1 | Early 2006 | <span style="color:red"> NO </span>  | 32-Bit CPU limitation |
| MacBookPro1,2 | ^^ | ^^ | ^^ |
| MacBookPro2,1 | Late 2006 | ^^ | 32-Bit Firmware limitation |
| MacBookPro2,2 | Late 2006 | ^^ | ^^ |
| MacBookPro3,1 | Mid-2007 | ^^ | - Requires SSE4.1 CPU |
| MacBookPro4,1 | Early 2008 | <span style="color:#30BCD5"> YES </span> | - No GPU Acceleration in Big Sur<br/>- No AppleHDA(Audio) Patching implemented(yet)<br/>- No Wifi Patches implemented(yet) |
| MacBookPro5,1 | Late 2008 | ^^ | - No GPU Acceleration in Big Sur<br/>- No AppleHDA(Audio) Patching implemented(yet) |
| MacBookPro5,2 | Early 2009 | ^^ | ^^ |
| MacBookPro5,3 | Mid-2009 | ^^ | ^^ |
| MacBookPro5,4 | ^^ | ^^ | ^^ |
| MacBookPro5,5 | ^^ | ^^ | ^^ |
| MacBookPro6,1 | Mid-2010 | ^^ | ^^ |
| MacBookPro6,2 | ^^ | ^^ | ^^ |
| MacBookPro7,1 | ^^ | ^^ | ^^ |
| MacBookPro8,1 | Early 2011 | ^^ | - No GPU Acceleration in Big Sur<br/>- No AppleHDA(Audio) Patching implemented(yet)<br/>- Ethernet Connection Issues |
| MacBookPro8,2 | ^^ | ^^ | ^^ |
| MacBookPro8,3 | ^^ | ^^ | ^^ |
| MacBookPro9,1 | Mid-2012 | ^^ | <span style="color:green"> Everything is supported</span> |
| MacBookPro9,2 | ^^ | ^^ | ^^ |  
| MacBookPro10,1 | ^^ | ^^ | ^^ |
| MacBookPro10,2 | Late 2012 | ^^ | ^^ |

### Mac mini

| SMBIOS | Year | Supported | Comment |
| :--- | :--- | :--- | :--- |
| Macmini1,1 | Early 2006 | <span style="color:red"> NO </span> | 32-Bit CPU limitation |
| Macmini2,1 | Mid-2007 | ^^ | 32-Bit Firmware limitation |
| Macmini3,1 | Early 2009 | <span style="color:#30BCD5"> YES </span> | - No GPU Acceleration in Big Sur<br/>- No AppleHDA(Audio) Patching implemented(yet) |
| Macmini4,1 | Mid-2010 | ^^ | ^^ |
| Macmini5,1 | Mid-2011 | ^^ | - No GPU Acceleration in Big Sur<br/>- No AppleHDA(Audio) Patching implemented(yet)<br/>- Ethernet Connection Issues |
| Macmini5,2 | ^^ | ^^ | ^^ |
| Macmini5,3 | ^^ | ^^ | ^^ |
| Macmini6,1 | Late 2012 | ^^ | <span style="color:green"> Everything is supported</span> |
| Macmini6,2 | ^^ | ^^ | ^^ |

### iMac

| SMBIOS | Year | Supported | Comment |
| :--- | :--- | :--- | :--- |
| iMac4,1 | Early 2006 | <span style="color:red"> NO </span> | 32-Bit CPU limitation |
| iMac4,2 | Mid-2006 | ^^ | ^^ |
| iMac5,1 | Late 2006 | ^^ | 32-Bit Firmware limitation |
| iMac5,2 | ^^ | ^^ | ^^ |
| iMac6,1 | ^^ | ^^ | ^^ |
| iMac7,1 | Mid-2007 | <span style="color:#30BCD5"> YES </span> | - Requires an SSE4.1 CPU Upgrade<br/>- No GPU Acceleration in Big Sur<br/>- No AppleHDA(Audio) Patching implemented(yet)<br/>- No Wifi Patches implemented (yet) |
| iMac8,1 | Early 2008 | ^^ | - No GPU Acceleration in Big Sur<br/>- No AppleHDA(Audio) Patching implemented(yet)<br/>- No Wifi Patches implemented (yet) |
| iMac9,1 | Early 2009 | ^^ | - No GPU Acceleration in Big Sur<br/>- No AppleHDA(Audio) Patching implemented(yet) |
| iMac10,1 | Late 2009 | ^^ | ^^ |
| iMac11,1 | ^^ | ^^ | - No GPU Acceleration in Big Sur<br/>- No AppleHDA(Audio) Patching implemented(yet)<br/>- Ethernet Connection Issues |
| iMac11,2 | Mid-2010 | ^^ | ^^ |
| iMac11,3 | ^^ | ^^ | ^^ |
| iMac12,1 | Mid-2011 | ^^ | ^^ |
| iMac12,2 | ^^ | ^^ | ^^ |
| iMac13,1 | Late 2012 | ^^ | <span style="color:green"> Everything is supported</span> |
| iMac13,2 | ^^ | ^^ | ^^ |
| iMac14,1 | Late 2013 | ^^ | ^^ |
| iMac14,2 | ^^ | ^^ | ^^ |
| iMac14,3 | ^^ | ^^ | ^^ |

### Mac Pro

| SMBIOS | Year | Supported | Comment |
| :--- | :--- | :--- | :--- |
| MacPro1,1 | Mid-2006 | <span style="color:red"> NO </span> | 32-Bit Firmware limitation |
| MacPro2,1 | Mid-2007 | ^^ | ^^ |
| MacPro3,1 | Early 2008 | <span style="color:#30BCD5"> YES </span> | - Requires an SSE4.1 CPU Upgrade<br/>- No AppleHDA(Audio) Patching implemented(yet) |
| MacPro4,1 | Early 2009 | ^^ | <span style="color:green"> Everything is supported as long as GPU is Metal capable </span> |
| MacPro5,1 | Mid-2010 | ^^ | ^^ |

### Xserve

| SMBIOS | Year | Supported | Comment |
| :--- | :--- | :--- | :--- |
| Xserve1,1 | Mid-2006 | <span style="color:red"> NO </span> | 32-Bit Firmware limitation |
| Xserve2,1 | Early 2008 | ^^ | ^^ |
| Xserve3,1 | Early 2009 | <span style="color:#30BCD5"> YES </span> | <span style="color:green"> Everything is supported as long as GPU is Metal capable </span> |