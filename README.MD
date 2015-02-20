# SuperFish Removal Utility

SuperFish was pre-installed on a limited group of Lenovo branded notebooks  beginning  September, 2014.  Lenovo recommends removing SuperFish and the SuperFish certificates from all systems.   

This utility will completely analyze your system for this problem and remove the SuperFish application, associated registry entries, files and security certificates, if needed. 

### Links
  - [Manual Removal Instructions](http://support.lenovo.com/us/en/product_security/superfish_uninstall)
  - [Lenovo Security Advisory](http://support.lenovo.com/us/en/product_security/superfish)
  - [Lenovo Statement](http://news.lenovo.com/article_display.cfm?article_id=1929)
  - [Lenovo License Agreement](http://support.lenovo.com/us/en/documents/ht100141)

#### Version
1.0.2.0

#### License
MPL 1.1

#### Technical Operations
  - Uninstall Superfish application ( %ProgramFiles(x86)%\Lenovo\VisualDiscovery\uninstall.exe)
  - Removal of Root certificate within Trusted Root Certification Authorities ("Superfish, Inc")
  - Removal of Root certificate within Firefox and Thunderbird certificate stores ("Superfish, Inc")
  - Removal of remaining registry items under HKEY_LOCAL_MACHINE\SOFTWARE\Wow6432Node\VisualDiscovery
  - Removal of remaining .ini and .log files
        * %SystemRoot%\SysWOW64\VisualDiscovery.ini
        * %SystemRoot%\SysWOW64\VisualDiscoveryOff.ini
        * %SystemRoot%\System32\VisualDiscoveryOff.ini
        * %TEMP%\VisualDiscoveryr.log
