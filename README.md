# geoip-update [![GitHub Release](https://img.shields.io/github/release/extremeshok/geoip-update.svg?label=Latest)](https://github.com/extremeshok/geoip-update/releases/latest)

## Maintained and provided by https://eXtremeSHOK.com

## Description
The geoip-update script provides a simple and efficient way to update and download the latest geoip datatabases

## FYI
Unlike other maxmind database update scripts, this will only download the databases when they have been updated. The databases are extracted directly to the geoip dir and as such this script does not use a temp dir and a copy. The script will also create symbolic links to alias the various database names to legacy database names

### Quick Install Guide
* Download the script
* Set 755 permissions on the script
* Run the the script

### Version 2.0.0
 - eXtremeSHOK.com Maintenance
 - Initial Public Release

### Version 1.x.x
 - eXtremeSHOK.com Internal


### Example of the GeoIP database dir
````
ls -laFh /usr/share/GeoIP
total 93M
drwxr-xr-x+  2 root root   16 May 12 10:24 ./
drwxr-xr-x+ 70 root root   71 May 12 06:18 ../
-rw-r--r--   1 root root 858K May 12 10:24 GeoIP.dat
-rw-r--r--   1 root root 4.0M May 12 10:24 GeoIPASNum.dat
-rw-r--r--   1 root root 4.9M May 12 10:24 GeoIPASNumv6.dat
lrwxrwxrwx   1 root root   32 May 12 10:24 GeoIPCity.dat -> /usr/share/GeoIP/GeoLiteCity.dat
lrwxrwxrwx   1 root root   34 May 12 10:24 GeoIPCityv6.dat -> /usr/share/GeoIP/GeoLiteCityv6.dat
-rw-r--r--   1 root root 1.6M May 12 10:24 GeoIPv6.dat
-rw-r--r--   1 root root  63M May 12 10:24 GeoLite2-City.mmdb
-rw-r--r--   1 root root 2.2M May 12 10:24 GeoLite2-Country.mmdb
lrwxrwxrwx   1 root root   31 May 12 10:24 GeoLiteASNum.dat -> /usr/share/GeoIP/GeoIPASNum.dat
lrwxrwxrwx   1 root root   33 May 12 10:24 GeoLiteASNumv6.dat -> /usr/share/GeoIP/GeoIPASNumv6.dat
-rw-r--r--   1 root root  22M May 12 10:24 GeoLiteCity.dat
-rw-r--r--   1 root root  22M May 12 10:24 GeoLiteCityv6.dat
lrwxrwxrwx   1 root root   26 May 12 10:24 GeoLiteCountry.dat -> /usr/share/GeoIP/GeoIP.dat
lrwxrwxrwx   1 root root   28 May 12 10:24 GeoLiteCountryv6.dat -> /usr/share/GeoIP/GeoIPv6.dat
````