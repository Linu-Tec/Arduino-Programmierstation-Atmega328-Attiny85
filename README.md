# Arduino-Programmierstation-Atmega328-Attiny85
Arduino Programmierstation Atmega328 &amp; Attiny85

Hier ist der Link zu den Platinen: https://www.pcbway.com/project/shareproject/Temperaturmessstation_34478d1d.html

Und hier könnt ihr selber Platinen bestellen: https://pcbway.com/g/Bm3OZF

![PCBWay-logo](https://github.com/Linu-Tec/Arduino-Programmierstation-Atmega328-Attiny85/assets/70856050/44f13653-726e-4d82-9f55-a3f83fe6b401)




Nur den Link einfügen (Arduino IDE), jeder Link in eine eigene Zeile!
https://raw.githubusercontent.com/damellis/attiny/ide-1.6.x-boards-manager/package_damellis_attiny_index.json


(https://docs.arduino.cc/built-in-examples/arduino-isp/ArduinoToBreadboard#minimal-circuit-eliminating-the-external-clock)

Minimal Circuit (Eliminating the External Clock)
If you don't have the extra 16 MHz crystal and 18-22 picofarad capacitors used in the above examples, you can configure the ATmega328P to use its internal 8 MHz RC oscillator as a clock source instead. (You don't really need the 10K pullup resistor on the reset pin either, so we remove it to get a truly minimal configuration.)

You'll need to install support for an additional hardware configuration:

Download this hardware configuration archive: breadboard-1-6-x.zip, Breadboard1-5-x.zip or Breadboard1-0-x.zip depending on which IDE you use.

Create a "hardware" sub-folder in your Arduino sketchbook folder (whose location you can find in the Arduino preferences dialog). If you've previously installed support for additional hardware configuration, you may already have a "hardware" folder in your sketchbook.

Move the breadboard folder from the zip archive to the "hardware" folder of your Arduino sketchbook.

Restart the Arduino software.

You should see "ATmega328 on a breadboard (8 MHz internal clock)" in the Tools > Board menu.


Übersetzt:
Minimale Schaltung (Eliminierung des externen Takts) Wenn Sie nicht über den zusätzlichen 16-MHz-Quarz und die 18–22 Picofarad-Kondensatoren verfügen, die in den obigen Beispielen verwendet wurden, können Sie den ATmega328P so konfigurieren, dass er stattdessen seinen internen 8-MHz-RC-Oszillator als Taktquelle verwendet. (Den 10K-Pullup-Widerstand am Reset-Pin benötigen Sie auch nicht wirklich, daher entfernen wir ihn, um eine wirklich minimale Konfiguration zu erhalten.)

Sie müssen Unterstützung für eine zusätzliche Hardwarekonfiguration installieren:

Laden Sie dieses Hardware-Konfigurationsarchiv herunter: breadboard-1-6-x.zip, Breadboard1-5-x.zip oder Breadboard1-0-x.zip, je nachdem, welche IDE Sie verwenden.

Erstellen Sie einen Unterordner „Hardware“ in Ihrem Arduino-Skizzenbuchordner (dessen Speicherort Sie im Arduino-Einstellungsdialog finden). Wenn Sie zuvor Unterstützung für zusätzliche Hardwarekonfiguration installiert haben, befindet sich möglicherweise bereits ein Ordner „Hardware“ in Ihrem Skizzenbuch.

Verschieben Sie den Breadboard-Ordner aus dem Zip-Archiv in den Ordner „Hardware“ Ihres Arduino-Skizzenbuchs.

Starten Sie die Arduino-Software neu.

Im Menü „Extras > Board“ sollte „ATmega328 auf einem Steckbrett (8 MHz interner Takt)“ angezeigt werden.
