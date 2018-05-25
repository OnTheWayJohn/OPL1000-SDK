## Release Version:
SDK Package: 1.0.1.18
Patch_Lib : 1622 
ROM_CODE: 809    

## Release Date:  2018/05/25

## Function & Feature Update
1. Below documents are updated: 
 1.1 OPL1000-AT-instruction-set-and-examples: R03, correct some description errors. 
 1.2 OPL1000-WIFI-BLE-API-guide: v1.0.1.18, updated several APIs' parameters description.   
2. Add three new example codes:
 2.1 I2C slave example. User need to connect an external I2C Master device to communicate with OPL1000 DEVKIT 
 2.2 Log on/off setting example. This example shows how to enable/disable ROM internal module and user application log information   
 2.3 http request example, provides two solution. One is based on CMSIS RTOS, the other is based on FreeRTOS.   
3. Update peripheral PWM example. Provide a complex setting mode to reach higher precision duty rate. 
4. Improved stability on AP connection    
5. http request example location: SDK\APS_PATCH\examples\protocols   
6. Log on/off setting example location: SDK\APS_PATCH\examples\get_started\log
7. I2C slave example location: SDK\APS_PATCH\examples\peripherals\i2c_slave

## Bug Fix List 
1. Fix a bug in auto-connection operation
2. Fix several bugs in BLE AT commands 

## Notes List 
1. Protocol examples such as https, tcp client/server etc. are on-developing 

*****

## Release Version:
SDK Package: 1.0.1.17 
Patch_Lib : 1516 
ROM_CODE: 809    

## Release Date:  2018/05/18

## Function & Feature Update
1. Below documents are updated: 
 1.1 OPL1000-AT-instruction-set-example: R02, add AT instruction example 
 1.2 OPL1000-DEVKIT-getting-start-guide: R02, add J-link emulator selection etc. 
 1.3 OPL1000-patch-download-tool-user-guide: R02, update according to v0.15 SW 
 1.4 OPL1000-SDK-Development-guide: R02, add log output setting section 
 1.5 OPL1000-SDK-getting-start-guide: R02, update download tool operation figures. 
 1.6 OPL1000-WIFI-BLE-API-guide: v1.0.1.17, several APIs' parameter type are changed.   
2. Firmware download tool is updated to v0.15, provide log message saving function. 
3. Support AT UART download patch bin file function. (need M3 bin file support AT UART download instruction)    
4. Add a demonstration folder "Demo\BLE_Config_AP" which show how to use OPL1000 BLE setup WIFI network 
5. Add API that support to turn ON/OFF show-Log on Debug-UART port 
6. Update formula of RSSI estimation

## Bug Fix List 


## Notes List 
1. Protocol examples are on-developing 

*****

## Release Version:
SDK Package: 1.0.1.16 
Patch_Lib : 1488 
ROM_CODE: 809    

## Release Date:  2018/05/11

## Function & Feature Update
1. WIFI: 802.11b station 
2. BLE: BLE 4.2 slave 
3. Firmware download supports from both APS and AT UART port  
4. Example codes include: peripheral, WIFI, BLE, BLEWIFI.  
5. Provide 6 documents include DEVKIT and SDK getting start, SDK/App development guide, AT command and API introduction, tool use guide etc. 
6. Provide 2 auxiliary tools, firmware download tool and pin-mux setting tool. 
7. Provide 2 UART driver: one is DEVKIT UART driver, the other is CH340 UART winXP driver which is used for APS UART port.  

## Bug Fix List 


## Notes List 
1. Trace log has disorder phenomenon
2. Protocol examples are on-developing 
3. System examples are on-developing 


