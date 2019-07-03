# How-to-build-a-Screensaver-in-XBian-with-Raspberry-Pi
_________________________________________________________________________________________________________________
Digitaler Bilderrahmen mit XBian und Kodi (Tutorial in English: https://github.com/PPrzemko/digital-photo-frame)
_________________________________________________________________________________________________________________
Vorbereitung:


1x Raspberry Pi 2 oder 3

1x Windows (ab 7)

1x SD-Karte mindestens 8 Gigabyte (beachten Sie: Zur Sicherheit vorher Kontrollieren das nur 1. Partition vorhanden ist)

1x SD Karten Slot. (Flashen geht mit oder ohne SD-Karten Adapter)

____________________________________________________________________________________________________________________

Laden Sie sich den XBian Installer herunter und starten Sie diesen. Im Hauptmenü können Sie ihr Raspberry Pi Modell auswählen.
Wir empfehlen mindestens einen Rasperry Pi Modell 3. Nach einem Klick auf "OK" können Sie nun in Schritt 2. eine Version von XBian wählen. Im zweifel die voreinstellung beibehalten. In Schritt 3 wählen Sie ihre SD-Karte aus.

Kopieren Sie sämtlichen "zip" Dateien auf den USB-Stick.

_____________________________________________________________________________________________________________________

Nachdem Sie die SD-Karte eingesteckt, die Internetverbindung über LAN hergestellt haben, einen Bildschirm, Maus und Tastatur angeschlossen haben können Sie den Raspberry Pi nun das erste mal mit Strom versorgen.

Wenn Kodi erfolgreich hochgefahren ist, gelangen Sie über das Einstellungsrad oben Links in die Konfigurationsübersicht.
Hier gehen Sie auf den Reiter Add-ons und gelangen in den Add-on browser.

Stecken Sie nun den vorbereiteten USB-Stick ein.

Wählen Sie den Eintrag "Install from zip file" aus und bestätigen Sie ihren USB-Stick. Mit einem Linksklick auf die entsprechende "zip" Datei wird diese automatisch installiert. Beachten Sie die Reihenfolge, manche Packete müssen vorher installiert werden, dies zeigt ihnen eine Fehlermeldung oben Rechts im Bildschirm.

Nachdem Sie nun alle Packete Installiert haben, starten Sie den Raspberry Pi neu. Drücken Sie die Taste "Esc" bis Sie wieder im Hauptmenü sind und klicken Sie oben Links auf das Power Symbol.
_______________________________________________________________________________________________________________________
Nach dem Neustart gehen Sie wieder in die Einstellungen und wählen diesmal "Interface" aus. Hier gibt es den Eintrag "Screensaver" mit dem Unterpunkt "Screensaver mode". Hier tauchen nun die Installierten Add-on's auf. Wählen Sie nun "Picture Slideshow Screensaver" aus. Alle weiteren Einstellungen finden Sie in der "Screensaver" spalte bei "Interface". Beachten Sie das unten links bei dem Einstellungsrad "Expert" steht.

Wenn Sie ihre Bilder nicht auf dem Raspberry Pi sondern in einer Cloud oder einem NAS/Netzwerkfreigabe speichern, können Sie diesen Pfad über "Screensaver" - "Settings" - "Image Folder" - "Folder" einlesen. Wir empfehlen das stabilere SMB Zugriffsverfahren. Beachten Sie das gegebenfalls ein neuer Benutzer und eine entsprechende Freigabe auf die Bilder erzeugt werden müssen. (Siehe https://github.com/globleTech/Digitaler-Bilderrahmen-mit-dem-Raspberry-Pi/tree/QNAP)
______________________________________________________________________________________________________________________________
Info: Der Bildschirmschoner braucht mindestens 1. Minute bis er startet.

Falls Sie nach dem Start des Raspberry Pi's eine Wetteranzeige verwenden möchten können Sie die "Yahoo Wetter" Pakete ebenfalls installieren.

______________________________________________________________________________________________________________________________
©globleTech
