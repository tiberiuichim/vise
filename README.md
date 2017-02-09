Vise - personal customizations
==============================

To install:

* clone original, in ~/work/vise, make a virtualenv inside ~/work/vise
* notice dependencies in dependencies.txt
* yaourt -S libsodium
* bin/pip install pyyaml pyqt5 apsw 

* install rapydscript-ng with npm (``~/Software/node4/bin/npm install -g rapydscript-ng``)
* add node to $PATH (``set PATH $PATH ~/Software/node4/bin/`` )
* generate client libs using instructions ``rapydscript --js-version 6 --cache-dir ~/work/vise/.build-cache ~/work/vise/client/main.pyj > ~/work/vise/resources/vise-client.js``
* start vise with:

```
cd work/vise
python3 .
```
