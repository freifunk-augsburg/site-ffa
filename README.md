# Development Version 

## 2015/11 Änderungen für Development Version ffmdev-x.y
* Vorbereitung auf das anstehende [Gluon Release v2015.2 dev](http://gluon.readthedocs.org/en/latest/releases/v2015.2.html)
* [Vorbereitung 802s.11 mesh](http://gluon.readthedocs.org/en/latest/releases/v2015.2.html#site-changes) (standardmäßig deaktiv, jedoch per Konfigmodus aktivierbar)
* Langsames 'salsa2012+gmac' entfernt. [Jetzt nur noch 'salsa2012+umac'](http://gluon.readthedocs.org/en/latest/releases/v2014.4.html#fastd-v16)
* ['Roles'](http://gluon.readthedocs.org/en/latest/features/roles.html) vorbereitet
* Konfigurationsseite jetzt in Deutsch und Englisch


### Bekannte Probleme
* Bei Gluon 2015.2 ist das Aktivieren des Konfigurationsmoduses etwas hakelig. Die optische Reboot-Rückmeldung über die LEDs kommt erst nach ca. 10 Sekunden.

## Weitere Änderungen seit der letzten Stable

* 5ghz stabilisiert, Wechsel auf ht20
* peer-Limit auf 1 reduziert
* radvd für öffentliches IPv6-Netz deaktiviert und für ULA-Netz aktiviert
* Neue Funktion: Verschlüsselung von Mesh-VPN kann abgeschaltet werden
* Neue Funktion: Wifi-Konfigurationspaket hinzugefügt
* Neue Funktion: Mesh-VPN ist standardmäßig aktiv 


# Git cheat-sheet 
## aktuellen gluon-branch nach dev ziehen
git fetch freifunk-gluon
git log freifunk-gluon/master
git checkout $whatevercommit
git branch -d dev
git checkout -b dev
git push --set-upstream origin dev

Bei Bedarf mit cherry-pick eigene commits wieder reinziehen
