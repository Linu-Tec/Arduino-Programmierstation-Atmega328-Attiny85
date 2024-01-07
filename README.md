# Arduino-Programmierstation-Atmega328-Attiny85
Arduino Programmierstation Atmega328 &amp; Attiny85

Hier ist der Link zu den Platinen: https://www.pcbway.com/project/shareproject/Arduino_Programmierstation_Atmega328_Attiny85_442d283b.html

Und hier könnt ihr selber Platinen bestellen: https://pcbway.com/g/Bm3OZF

![PCBWay-logo](https://github.com/Linu-Tec/Arduino-Programmierstation-Atmega328-Attiny85/assets/70856050/44f13653-726e-4d82-9f55-a3f83fe6b401)




Nur den Link einfügen (Arduino IDE), jeder Link in eine eigene Zeile!
https://raw.githubusercontent.com/damellis/attiny/ide-1.6.x-boards-manager/package_damellis_attiny_index.json



(https://docs.arduino.cc/built-in-examples/arduino-isp/ArduinoToBreadboard#minimal-circuit-eliminating-the-external-clock)

>Minimal Circuit (Eliminating the External Clock)
If you don't have the extra 16 MHz crystal and 18-22 picofarad capacitors used in the above examples, you can configure the ATmega328P to use its internal 8 MHz RC oscillator as a clock source instead. (You don't really need the 10K pullup resistor on the reset pin either, so we remove it to get a truly minimal configuration.)

>You'll need to install support for an additional hardware configuration:

>Download this hardware configuration archive: [breadboard-1-6-x.zip](https://www.arduino.cc/en/uploads/Tutorial/breadboard-1-6-x.zip?_gl=1*dxfyj7*_ga*Mzc0NzQ1OTUuMTY4NDAwODAxMQ..*_ga_NEXN8H46L5*MTcwNDM4ODc2NC43My4xLjE3MDQzODk0MzAuMC4wLjA.*_fplc*ejdjNHhKQzQyWmRZcmcybCUyRkpJZHB0YkY1aVdNbmx1eTZHY2NJaHo5SFJxc0hhMzd5c1BqcFZ2WFRXbHA4Y282bjlJaE5ZVVo0UGJFdXFpVmJGVzNJS2w1T1lQQ0ZMeGxQRm94dU9NZXVsOTBIVUdORFRtSlJoVWduSW1yTXclM0QlM0Q.), [Breadboard1-5-x.zip](https://www.arduino.cc/en/uploads/Tutorial/Breadboard1-5-x.zip?_gl=1*dxfyj7*_ga*Mzc0NzQ1OTUuMTY4NDAwODAxMQ..*_ga_NEXN8H46L5*MTcwNDM4ODc2NC43My4xLjE3MDQzODk0MzAuMC4wLjA.*_fplc*ejdjNHhKQzQyWmRZcmcybCUyRkpJZHB0YkY1aVdNbmx1eTZHY2NJaHo5SFJxc0hhMzd5c1BqcFZ2WFRXbHA4Y282bjlJaE5ZVVo0UGJFdXFpVmJGVzNJS2w1T1lQQ0ZMeGxQRm94dU9NZXVsOTBIVUdORFRtSlJoVWduSW1yTXclM0QlM0Q.) or [Breadboard1-0-x.zip](https://www.arduino.cc/en/uploads/Tutorial/Breadboard1-0-x.zip?_gl=1*957kp5*_ga*Mzc0NzQ1OTUuMTY4NDAwODAxMQ..*_ga_NEXN8H46L5*MTcwNDM4ODc2NC43My4xLjE3MDQzODk0MzAuMC4wLjA.*_fplc*ejdjNHhKQzQyWmRZcmcybCUyRkpJZHB0YkY1aVdNbmx1eTZHY2NJaHo5SFJxc0hhMzd5c1BqcFZ2WFRXbHA4Y282bjlJaE5ZVVo0UGJFdXFpVmJGVzNJS2w1T1lQQ0ZMeGxQRm94dU9NZXVsOTBIVUdORFRtSlJoVWduSW1yTXclM0QlM0Q.) depending on which IDE you use.

>Create a "hardware" sub-folder in your Arduino sketchbook folder (whose location you can find in the Arduino preferences dialog). If you've previously installed support for additional hardware configuration, you may already have a "hardware" folder in your sketchbook.

>Move the breadboard folder from the zip archive to the "hardware" folder of your Arduino sketchbook.

>Restart the Arduino software.

>You should see "ATmega328 on a breadboard (8 MHz internal clock)" in the Tools > Board menu.



**Übersetzt:**

>Minimale Schaltung (Eliminierung des externen Takts) Wenn Sie nicht über den zusätzlichen 16-MHz-Quarz und die 18–22 Picofarad-Kondensatoren verfügen, die in den obigen Beispielen verwendet wurden, können Sie den ATmega328P so konfigurieren, dass er stattdessen seinen internen 8-MHz-RC-Oszillator als Taktquelle verwendet. (Den 10K-Pullup-Widerstand am Reset-Pin benötigen Sie auch nicht wirklich, daher entfernen wir ihn, um eine wirklich minimale Konfiguration zu erhalten.)

>Sie müssen Unterstützung für eine zusätzliche Hardwarekonfiguration installieren:

>Laden Sie dieses Hardware-Konfigurationsarchiv herunter: [breadboard-1-6-x.zip](https://www.arduino.cc/en/uploads/Tutorial/breadboard-1-6-x.zip?_gl=1*dxfyj7*_ga*Mzc0NzQ1OTUuMTY4NDAwODAxMQ..*_ga_NEXN8H46L5*MTcwNDM4ODc2NC43My4xLjE3MDQzODk0MzAuMC4wLjA.*_fplc*ejdjNHhKQzQyWmRZcmcybCUyRkpJZHB0YkY1aVdNbmx1eTZHY2NJaHo5SFJxc0hhMzd5c1BqcFZ2WFRXbHA4Y282bjlJaE5ZVVo0UGJFdXFpVmJGVzNJS2w1T1lQQ0ZMeGxQRm94dU9NZXVsOTBIVUdORFRtSlJoVWduSW1yTXclM0QlM0Q.), [Breadboard1-5-x.zip](https://www.arduino.cc/en/uploads/Tutorial/Breadboard1-5-x.zip?_gl=1*dxfyj7*_ga*Mzc0NzQ1OTUuMTY4NDAwODAxMQ..*_ga_NEXN8H46L5*MTcwNDM4ODc2NC43My4xLjE3MDQzODk0MzAuMC4wLjA.*_fplc*ejdjNHhKQzQyWmRZcmcybCUyRkpJZHB0YkY1aVdNbmx1eTZHY2NJaHo5SFJxc0hhMzd5c1BqcFZ2WFRXbHA4Y282bjlJaE5ZVVo0UGJFdXFpVmJGVzNJS2w1T1lQQ0ZMeGxQRm94dU9NZXVsOTBIVUdORFRtSlJoVWduSW1yTXclM0QlM0Q.) or [Breadboard1-0-x.zip](https://www.arduino.cc/en/uploads/Tutorial/Breadboard1-0-x.zip?_gl=1*957kp5*_ga*Mzc0NzQ1OTUuMTY4NDAwODAxMQ..*_ga_NEXN8H46L5*MTcwNDM4ODc2NC43My4xLjE3MDQzODk0MzAuMC4wLjA.*_fplc*ejdjNHhKQzQyWmRZcmcybCUyRkpJZHB0YkY1aVdNbmx1eTZHY2NJaHo5SFJxc0hhMzd5c1BqcFZ2WFRXbHA4Y282bjlJaE5ZVVo0UGJFdXFpVmJGVzNJS2w1T1lQQ0ZMeGxQRm94dU9NZXVsOTBIVUdORFRtSlJoVWduSW1yTXclM0QlM0Q.), je nachdem, welche IDE Sie verwenden.

>Erstellen Sie einen Unterordner „Hardware“ in Ihrem Arduino-Skizzenbuchordner (dessen Speicherort Sie im Arduino-Einstellungsdialog finden). Wenn Sie zuvor Unterstützung für zusätzliche Hardwarekonfiguration installiert haben, befindet sich möglicherweise bereits ein Ordner „Hardware“ in Ihrem Skizzenbuch.

>Verschieben Sie den Breadboard-Ordner aus dem Zip-Archiv in den Ordner „Hardware“ Ihres Arduino-Skizzenbuchs.

>Starten Sie die Arduino-Software neu.

>Im Menü „Extras > Board“ sollte „ATmega328 auf einem Steckbrett (8 MHz interner Takt)“ angezeigt werden.


Bilder-Serie:
Datei -> Beispiele -> 11.ArduinoISP -> ArduinoISP
![2024-01-04 (0)](https://github.com/Linu-Tec/Arduino-Programmierstation-Atmega328-Attiny85/assets/70856050/ca91dd7a-0dbb-415c-b411-43cbed14db0a)
Werkzeug -> Board, Port, Prozessor auswählen
![2024-01-04 (1)](https://github.com/Linu-Tec/Arduino-Programmierstation-Atmega328-Attiny85/assets/70856050/e9f1290d-f413-404e-a7cd-5e4691cd05ea)
ArduinoISP.ino Hochladen
![2024-01-04 (2)](https://github.com/Linu-Tec/Arduino-Programmierstation-Atmega328-Attiny85/assets/70856050/87c9d4a5-7c1a-4541-8ab0-5d612ecbe7e2)
Datei -> Beispiele -> 01.Basics -> Blink
![2024-01-04 (3)](https://github.com/Linu-Tec/Arduino-Programmierstation-Atmega328-Attiny85/assets/70856050/4ce966e7-80a0-4e38-abe7-8c73e9dc87d5)
Datei -> Einstellungen...
![2024-01-04 (4)](https://github.com/Linu-Tec/Arduino-Programmierstation-Atmega328-Attiny85/assets/70856050/542408b0-12ba-47bc-814f-f52480b49687)
Zustätzliche Boards verwalten und diesen Link einfügen (https://raw.githubusercontent.com/damellis/attiny/ide-1.6.x-boards-manager/package_damellis_attiny_index.json)
![2024-01-04 (5)](https://github.com/Linu-Tec/Arduino-Programmierstation-Atmega328-Attiny85/assets/70856050/8c0775f4-21b3-414b-a164-e7edbec751a8)
Werkzeug -> Board (Breadboard-avr(im Sketchbook -> Atmega328)
![2024-01-04 (6)](https://github.com/Linu-Tec/Arduino-Programmierstation-Atmega328-Attiny85/assets/70856050/eec29df4-d782-44f4-9591-624b668f9aa9)
Werkzeug -> Programmer -> "Arduino as ISP" -> Bootloader brennen
![2024-01-04 (7)](https://github.com/Linu-Tec/Arduino-Programmierstation-Atmega328-Attiny85/assets/70856050/509a6f9a-9562-4b93-9c56-a7455b826ab2)
Sketch -> Mit Programmer hochladen -> Blink.ino
![2024-01-04 (8)](https://github.com/Linu-Tec/Arduino-Programmierstation-Atmega328-Attiny85/assets/70856050/c0113971-dba2-45b8-96e9-60ab3e0b43fd)
Board-Verwaltung -> Attiny Lib installieren
![2024-01-04 (9)](https://github.com/Linu-Tec/Arduino-Programmierstation-Atmega328-Attiny85/assets/70856050/891139f6-da87-4ada-b799-c0704979d28e)
Werkzeug -> Board (Attiny Microcontrollers(Attiny25/45/85)
![2024-01-04 (10)](https://github.com/Linu-Tec/Arduino-Programmierstation-Atmega328-Attiny85/assets/70856050/49a88aef-e25e-4616-be3e-2fe6d8d58af0)
Werkzeug -> Prozessor "Attiny85" auswählen
![2024-01-04 (11)](https://github.com/Linu-Tec/Arduino-Programmierstation-Atmega328-Attiny85/assets/70856050/ff579d12-6d30-4b40-93c4-1cefe546a323)
Werkzeug -> Programmer -> "Arduino as ISP" -> Bootloader brennen
![2024-01-04 (12)](https://github.com/Linu-Tec/Arduino-Programmierstation-Atmega328-Attiny85/assets/70856050/59f9cfc6-ffbd-440a-8bed-f37f1441a0fb)
Sketch -> Mit Programmer hochladen -> Blink.ino (**LED_BUILTIN zu 2 ändern**)
![2024-01-04 (13)](https://github.com/Linu-Tec/Arduino-Programmierstation-Atmega328-Attiny85/assets/70856050/16295de9-3a66-4c11-b8a0-c2ae69d093d0)



