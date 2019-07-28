# Upload .bin project files here for OTA
- https://github.com/espressif/ESP8266_RTOS_SDK/tree/master/examples/system/ota/simple_ota_example

### Get GitHub root certificate
- chrome -> settings -> advanced -> manage certificates -> (tab) trusted root certificate authorities
  - 1. export ```[DigiCert High Assurance EV Root CA]``` as ```Base-64 encoded X.509 (.CER)```
  
    <img src="https://github.com/gearsmotion789/OTA/blob/master/esp8266/images/certs.PNG" width="400">
    
  - 2. rename to ```ca_cert.pem``` format
  
### Get HTTPS root certificate for Amazon API Gateway requests
- export ```[Starfield Class 2 Certification Authority]``` as ```Base-64 encoded X.509 (.CER)```

###### References
- http://dev.ti.com/tirex/content/simplelink_academy_cc32xxsdk_1_13_00_29/modules/wifi_ota/wifi_ota.html
- Amazon API Gateway: https://e2e.ti.com/support/wireless-connectivity/wifi/f/968/t/748248
