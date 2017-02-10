
## FHEM Style: hunger89
Mit diesem Style wird die FHEM-Oberfläche etwas anschaulicher.
inspiriert von Matthias Kleine mit seiner Ineternetseit haus-automatisierung.com

https://haus-automatisierung.com/hardware/fhem/2016/05/16/fhem-tutorial-reihe-part-5-look-and-feel-von-fhem-veraendern.html

## Installation

1. Laden der Quellen

```
sudo apt-get install git-core
cd /opt/fhem/www

sudo git clone https://github.com/hunger89/FHEM.git Hunger89-com
```

2. Default style aktivieren

3. Design aktivieren

Danach muss auf dem WEB-Device das entsprechende Attribut gesetzt werden. In diesem Fall

```
attr CssFiles hausautomatisierung-com/styles.css
```

Einmal speichern und neu laden - fertig.
