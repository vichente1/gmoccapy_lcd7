# gmoccapy_lcd7
Interfaz gráfica modificada para pantallas lcd de 7 pulgadas táctil con resolución de 800x480, probada en la plataforma Beaglebone Black con la Imagen Debian Machinekit.

# Instalación

  - Copiar el archivo bin/gmoccapy_lcd7 a la carpeta /usr/bin/
  - Copiar la carpeta share/gmoccapy_lcd7 a la carpeta /usr/share/
  - Instalar matchbox
  - Copiar archivo keyboard-cnc.xml a la carpeta /usr/share/matchbox-keyboard

```sh
$ cd gmoccapy_lcd7/
$ sudo cp bin/gmoccapy_lcd7 /usr/bin/
$ sudo chmod a+x /usr/bin/gmoccapy_lcd7
$ sudo cp -r share/gmoccapy_lcd7/ /usr/share/
$ sudo apt-get update
$ sudo apt-get install matchbox
$ sudo cp keyboard-cnc.xml /usr/share/matchbox-keyboard
$ sudo chmod a+x /usr/share/matchbox-keyboard/keyboard-cnc.xml
```
