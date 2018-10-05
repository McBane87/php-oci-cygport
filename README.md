# php-oci-cygport

### Howto Build/Install (PHP5)
1. Make sure you have `cygport`, `php`, `php-devel` installed
2. `export ORACLE_INSTC=/path/to/instant_client_12_2`
3. `export ORACLE_VERSION=12.1 #Needs to be always x.1 even if version is x.2`
4. `cygport php56-oci.cygport prep`  
5. `cygport php56-oci.cygport compile`  
6. `cygport php56-oci.cygport install`  
7.
   For i686:   `cp -avr php-5.6.38-1.i686/inst/* /`  
   For x86_64: `cp -avr php-5.6.38-1.x86_64/inst/* /`  
   
### Howto Build/Install (PHP7)
1. Make sure you have `cygport`, `php`, `php-devel` installed
2. `export ORACLE_INSTC=/path/to/instant_client_12_2`
3. `export ORACLE_VERSION=12.1 #Needs to be always x.1 even if version is x.2`
4. `cygport php71-oci.cygport prep`  
5. `cygport php71-oci.cygport compile`  
6. `cygport php71-oci.cygport install`  
7.
   For i686:   `cp -avr php-7.1.22-1.i686/inst/* /`  
   For x86_64: `cp -avr php-7.1.22-1.x86_64/inst/* /`
