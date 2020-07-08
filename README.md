## Augsburg Babel-Development Version

#v0.0.1_babel-buggy
git clone -b christf_next https://github.com/christf/gluon gluon-auto
cd gluon-auto
git clone https://github.com/freifunk-augsburg/site-ffa.git site
make update
./site/build.sh -d -v -j2 (-h for help)





#v0.0.1_babel-work
Etwas gepatches Gluon, angereichert mit den Configs für Freifunk-Augsburg et viola nach ca. 8 Stunden compiletime habt Ihr im output-Ordner Firmwares liegen
git clone -b christf_next https://github.com/christf/gluon
cd gluon
git clone https://github.com/freifunk-augsburg/site-ffa.git site
make update
make GLUON_TARGET=ar71xx-generic


#### Known Issues
Entwicklerversion. Es ist mehr kaputt als geht.
