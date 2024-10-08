==================
pygeocoder 1.3.0
==================
Xiao Yu

*Based on googlemaps 1.0.2 by John Kleint*

README
------
This is a Python wrapper for Google Geocoding API V3

It allows you to directly convert an address to coordinates or vice versa. It also allows you to validate, format and split addresses into civic number, street name, city etc.

License
------
BSD

Dependencies
------------
It has dependency on the json module, included with Python versions 2.6 and later and available for download as simplejson for earlier versions. functools is needed and included in Python 2.5. Requirement for hmac is included with Python 2.2. hashlib depends on Python 2.5. base64 depends on Python 2.4.

requests library is needed and installed by setuptools.

It is developed on Python 2.7 but should work on earlier versions. It is also compatible with Python 3.


Installation
------------
You can install this package using pip:

	pip install pygeocoder

or download the source from http://code.xster.net/pygeocoder and install

	python setup.py install

Usage
-----
Please refer to http://code.xster.net/pygeocoder/wiki for help with usage


Contact Information
-------------------
Author: Xiao Yu
Internet: http://code.xster.net/pygeocoder

For comments, issues, requests, please contact via BitBucket at the above website


Changelog
---------
Version 1.3.0
Bug fixes to support Python 3.10:
* Fix ImportError for collections.abc.Iterator
* Remove unresolved unicode reference in GeocoderError.__unicode__ attribute

Version 1.2.5
More business key fix

Version 1.2.4
Business key signing fix

Version 1.2.3.1
Some pep8 cleanup

Version 1.2.3
Fixed business key crypto error
Added back simple API authentication method

Version 1.2.2
Added components restrictions in searches and location type getter in result

Version 1.2.1.1
Another dependency fix

Version 1.2.1
Proxy support

Version 1.2.0.3
setup.py dependency fix

Version 1.2.0.2
Minor setup.py Python 3 fix

Version 1.2.0.1
setup.py dependency fix

Version 1.2
Refactor and unit testing
Changed license to BSD
Python 3 compatibility
Business API account support

Version 1.1.4
Fixed UTF-8 and facilitated command line usage

Version 1.1.3
Made Geocoder methods static method while backward compatible

Version 1.1.2
Added address validation

Version 1.1.1
Returns GeocoderResult by default.
Result set accessible by iterator or index.

Version 1.1
Added GeocoderResult in order to ease field retrieval/result parsing.

Version 1.0
Working version an API V3.
