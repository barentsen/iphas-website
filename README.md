vphas-website
=============

Website for the [IPHAS](http://www.iphas.org) (IPHAS) astronomical survey project.
You can see the website in action at http://www.iphas.org.


Usage
-----

The website makes use of good-old Server Side Includes (SSI) which needs an SSI-enabled webserver to work. To test the website on your desktop, you can use the marvelous Python `ssi-server` as follows:

```
git clone https://github.com/danvk/ssi-server.git
git clone https://github.com/barentsen/iphas-website.git
cd iphas-website
python ../ssi-server/ssi_server.py
```

... and then simply point your browser at http://localhost:8000

Authors
-------
* Geert Barentsen
* Janet Drew
* IPHAS team

License
-------

Copyright (c) 2014 by the authors. All rights reserved.

This copyright notice does not apply to the external dependencies 
which are present in the `assets/` sub-directory, which includes 
bootstrap, jquery and font-awesome. Their copyright notice and
license information are found here:

* https://github.com/twbs/bootstrap/blob/master/LICENSE
* https://github.com/jquery/jquery/blob/master/MIT-LICENSE.txt
* https://github.com/FortAwesome/Font-Awesome/blob/master/README.md
