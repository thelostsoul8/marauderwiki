# Select APs
<p align="left">
  <img alt="ESP32 WROOM-32U" src="https://github.com/justcallmekoko/ESP32Marauder/blob/master/pictures/icons/keyboard_22.bmp?raw=true" width="100">
</p>

### Menu Location
`WiFi`>`General`>`Select APs`  

### Info
The ESP32 Marauder maintains a list of access points scanned with [Scan APs](scan-aps). If this option is selected, the full list of all access points scanned in the current session will be displayed on a scrollable list. In order to execute certain WiFi based attacks, acccess points from the list must be selected using this function. To select access points, simply traverse the list and click on the desired access points shown. Selected access points will be shown in red and will be marked as "active". Access points marked as active will be used in any WiFi based attacks that require specific targeting. Access points can be deselected by toggling them off in the list.  

The list of access points can be cleared by using [Clear APs](clear-aps). Subsequent scans will append access points to the current list. If the user is actively changing physical locations while scanning, it is recommended the list be cleared with each scan to avoid hogging memory.