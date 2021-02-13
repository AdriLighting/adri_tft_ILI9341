# adri_tft_ILI9341
 adri_tft_ILI9341

<pre>
Librairies
<details>
adri_tft_ILI9341                = https://github.com/AdriLighting/adri_tft_ILI9341
adri_tft_ILI9341_ESP            = https://github.com/AdriLighting/adri_tft_ILI9341_ESP
adri_tools_v2                   = https://github.com/AdriLighting/adri_tools_v2

esp8266/arduino                 = https://github.com/esp8266/Arduino/tree/master/libraries

Adafruit BusIO                  = https://github.com/adafruit/Adafruit_BusIO
Adafruit GFX Library            = https://github.com/adafruit/Adafruit-GFX-Library
XPT2046                         = http://github.com/spapadim/XPT2046
U8g2_for_Adafruit_GFX           = https://github.com/olikraus/U8g2_for_Adafruit_GFX
JPEGDecoder                     = https://github.com/Bodmer/JPEGDecoder
</details>
Dependency Graph
<details>
|-- [Adafruit BusIO] 1.4.1
|   |-- [Wire] 1.0
|   |-- [SPI] 1.0
|-- [Wire] 1.0
|-- [adri_tft_ILI9341] 1.0.0
|   |-- [SPI] 1.0
|   |-- [adri_tft_ILI9341_ESP] 1.0.1
|   |   |-- [Adafruit GFX Library] 1.10.2
|   |   |   |-- [Adafruit BusIO] 1.4.1
|   |   |   |   |-- [Wire] 1.0
|   |   |   |   |-- [SPI] 1.0
|   |   |   |-- [Wire] 1.0
|   |   |   |-- [SPI] 1.0
|   |   |-- [SPI] 1.0
|   |-- [Adafruit GFX Library] 1.10.2
|   |   |-- [Adafruit BusIO] 1.4.1
|   |   |   |-- [Wire] 1.0
|   |   |   |-- [SPI] 1.0
|   |   |-- [Wire] 1.0
|   |   |-- [SPI] 1.0
|   |-- [XPT2046] 0.1
|   |   |-- [SPI] 1.0
|   |-- [U8g2_for_Adafruit_GFX] 1.7.0
|   |   |-- [Adafruit GFX Library] 1.10.2
|   |   |   |-- [Adafruit BusIO] 1.4.1
|   |   |   |   |-- [Wire] 1.0
|   |   |   |   |-- [SPI] 1.0
|   |   |   |-- [Wire] 1.0
|   |   |   |-- [SPI] 1.0
|   |-- [JPEGDecoder] 1.8.0
|   |-- [adri_tools_v2] 1.0.0
|   |   |-- [ESP8266WiFi] 1.0
|   |   |-- [LittleFS(esp8266)] 0.1.0
|   |-- [ESP8266WiFi] 1.0
|   |-- [LittleFS(esp8266)] 0.1.0</details>
</pre>

<hr>

#### examples

adri_tft_ILI9341_func
<details>
platformio.ini
<details>
<pre>
[env:nodemcuv2]
platform=espressif8266
board=nodemcuv2
framework=arduino
lib_deps=Adafruit BusIO, Wire
lib_extra_dirs= ${env.lib_extra_dirs}
[platformio]
src_dir= ${env.src_dir}

</pre>
</details>
<pre>
Librairies
<details>
adri_tft_ILI9341                = https://github.com/AdriLighting/adri_tft_ILI9341
adri_tft_ILI9341_ESP            = https://github.com/AdriLighting/adri_tft_ILI9341_ESP
adri_tools_v2                   = https://github.com/AdriLighting/adri_tools_v2
adri_timer                      = https://github.com/AdriLighting/adri_timer

esp8266/arduino                 = https://github.com/esp8266/Arduino/tree/master/libraries

Adafruit BusIO                  = https://github.com/adafruit/Adafruit_BusIO
Adafruit GFX Library            = https://github.com/adafruit/Adafruit-GFX-Library
XPT2046                         = http://github.com/spapadim/XPT2046
U8g2_for_Adafruit_GFX           = https://github.com/olikraus/U8g2_for_Adafruit_GFX
JPEGDecoder                     = https://github.com/Bodmer/JPEGDecoder
</details>
Dependency Graph
<details>
|-- [Adafruit BusIO] 1.4.1
|   |-- [Wire] 1.0
|   |-- [SPI] 1.0
|-- [Wire] 1.0
|-- [adri_tft_ILI9341] 1.0.0
|   |-- [SPI] 1.0
|   |-- [adri_tft_ILI9341_ESP] 1.0.1
|   |   |-- [Adafruit GFX Library] 1.10.2
|   |   |   |-- [Adafruit BusIO] 1.4.1
|   |   |   |   |-- [Wire] 1.0
|   |   |   |   |-- [SPI] 1.0
|   |   |   |-- [Wire] 1.0
|   |   |   |-- [SPI] 1.0
|   |   |-- [SPI] 1.0
|   |-- [Adafruit GFX Library] 1.10.2
|   |   |-- [Adafruit BusIO] 1.4.1
|   |   |   |-- [Wire] 1.0
|   |   |   |-- [SPI] 1.0
|   |   |-- [Wire] 1.0
|   |   |-- [SPI] 1.0
|   |-- [XPT2046] 0.1
|   |   |-- [SPI] 1.0
|   |-- [U8g2_for_Adafruit_GFX] 1.7.0
|   |   |-- [Adafruit GFX Library] 1.10.2
|   |   |   |-- [Adafruit BusIO] 1.4.1
|   |   |   |   |-- [Wire] 1.0
|   |   |   |   |-- [SPI] 1.0
|   |   |   |-- [Wire] 1.0
|   |   |   |-- [SPI] 1.0
|   |-- [adri_tools_v2] 1.0.0
|   |   |-- [ESP8266WiFi] 1.0
|   |   |-- [LittleFS(esp8266)] 0.1.0
|   |-- [ESP8266WiFi] 1.0
|   |-- [LittleFS(esp8266)] 0.1.0
|   |-- [JPEGDecoder] 1.8.0
|-- [adri_timer] 1.0.0
|-- [adri_tools_v2] 1.0.0
|   |-- [ESP8266WiFi] 1.0
|   |-- [LittleFS(esp8266)] 0.1.0
|-- [ILI9341_esp_controls]
|   |-- [adri_tft_ILI9341_ESP] 1.0.1
|   |   |-- [Adafruit GFX Library] 1.10.2
|   |   |   |-- [Adafruit BusIO] 1.4.1
|   |   |   |   |-- [Wire] 1.0
|   |   |   |   |-- [SPI] 1.0
|   |   |   |-- [Wire] 1.0
|   |   |   |-- [SPI] 1.0
|   |   |-- [SPI] 1.0
|-- [JPEGDecoder] 1.8.0</details>
</pre>

</details>



adri_tft_ILI9341_init
<details>
platformio.ini
<details>
<pre>
[env:nodemcuv2]
platform=espressif8266
board=nodemcuv2
framework=arduino
lib_deps=Adafruit BusIO, Wire
lib_extra_dirs= ${env.lib_extra_dirs}
[platformio]
src_dir= ${env.src_dir}

</pre>
</details>
<pre>
Librairies
<details>
adri_tft_ILI9341                = https://github.com/AdriLighting/adri_tft_ILI9341
adri_tft_ILI9341_ESP            = https://github.com/AdriLighting/adri_tft_ILI9341_ESP
adri_tools_v2                   = https://github.com/AdriLighting/adri_tools_v2
adri_timer                      = https://github.com/AdriLighting/adri_timer
adri_tools                      = https://github.com/AdriLighting/adri_tools

esp8266/arduino                 = https://github.com/esp8266/Arduino/tree/master/libraries

Adafruit BusIO                  = https://github.com/adafruit/Adafruit_BusIO
Adafruit GFX Library            = https://github.com/adafruit/Adafruit-GFX-Library
XPT2046                         = http://github.com/spapadim/XPT2046
U8g2_for_Adafruit_GFX           = https://github.com/olikraus/U8g2_for_Adafruit_GFX
JPEGDecoder                     = https://github.com/Bodmer/JPEGDecoder
</details>
Dependency Graph
<details>
|-- [Adafruit BusIO] 1.4.1
|   |-- [Wire] 1.0
|   |-- [SPI] 1.0
|-- [Wire] 1.0
|-- [adri_tft_ILI9341] 1.0.0
|   |-- [SPI] 1.0
|   |-- [adri_tft_ILI9341_ESP] 1.0.1
|   |   |-- [Adafruit GFX Library] 1.10.2
|   |   |   |-- [Adafruit BusIO] 1.4.1
|   |   |   |   |-- [Wire] 1.0
|   |   |   |   |-- [SPI] 1.0
|   |   |   |-- [Wire] 1.0
|   |   |   |-- [SPI] 1.0
|   |   |-- [SPI] 1.0
|   |-- [Adafruit GFX Library] 1.10.2
|   |   |-- [Adafruit BusIO] 1.4.1
|   |   |   |-- [Wire] 1.0
|   |   |   |-- [SPI] 1.0
|   |   |-- [Wire] 1.0
|   |   |-- [SPI] 1.0
|   |-- [XPT2046] 0.1
|   |   |-- [SPI] 1.0
|   |-- [U8g2_for_Adafruit_GFX] 1.7.0
|   |   |-- [Adafruit GFX Library] 1.10.2
|   |   |   |-- [Adafruit BusIO] 1.4.1
|   |   |   |   |-- [Wire] 1.0
|   |   |   |   |-- [SPI] 1.0
|   |   |   |-- [Wire] 1.0
|   |   |   |-- [SPI] 1.0
|   |-- [JPEGDecoder] 1.8.0
|   |-- [adri_tools_v2] 1.0.0
|   |   |-- [ESP8266WiFi] 1.0
|   |   |-- [LittleFS(esp8266)] 0.1.0
|   |-- [ESP8266WiFi] 1.0
|   |-- [LittleFS(esp8266)] 0.1.0
|-- [adri_timer] 1.0.0
|-- [adri_tools] 1.0.0
|   |-- [ESP8266WiFi] 1.0
|   |-- [LittleFS(esp8266)] 0.1.0
|-- [ILI9341_esp_controls]
|   |-- [adri_tft_ILI9341_ESP] 1.0.1
|   |   |-- [Adafruit GFX Library] 1.10.2
|   |   |   |-- [Adafruit BusIO] 1.4.1
|   |   |   |   |-- [Wire] 1.0
|   |   |   |   |-- [SPI] 1.0
|   |   |   |-- [Wire] 1.0
|   |   |   |-- [SPI] 1.0
|   |   |-- [SPI] 1.0
|-- [JPEGDecoder] 1.8.0</details>
</pre>

</details>

<hr>
