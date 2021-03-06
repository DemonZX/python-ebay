python-ebay - Python Wrapper for eBay API
========================================

This project intends to create a simple python wrapper around eBay APIs.


How to Install
==============
1. Download [python-ebay][1] 
2. Rename: `config.ini.example` to `config.ini`
3. Configure `config.ini` to it's required values. You need to generate the values from eBay Developer Program [here][4]   
4. `python setup.py install`
   This will install the package.  
5. How to Use (see all operations in /examples):  
`from ebay.shopping import FindProducts`  
`print FindProducts("pen", "false", "10", "JSON")`


API Details
===========

The detailed list of eBay's API and it's short description is listed on our wiki page [here][2]. 
This list might not be current, please refer for the most recent list [here][3] on official eBay developer website.



  [1]: https://github.com/roopeshvaddepally/python-ebay/tarball/master
  [2]: https://github.com/roopeshvaddepally/python-ebay/wiki/List-of-eBay-APIs
  [3]: http://developer.ebay.com/products/overview
  [4]: http://developer.ebay.com/quickstartguide/


License
=======

Apache License, Version 2.0
Please refer to details here: http://www.apache.org/licenses/LICENSE-2.0.html


Contributors
===========
Eike Welk  
Utkarsh Sengar  
Roopesh Vaddepally  
Stephen Balaban  
hbtronix  
bogdanvarlamov  
patoch  
