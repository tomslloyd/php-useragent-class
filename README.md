# php-useragent-class
PHP User Agent Class, used for the following
 - Detect Browser and Version
 - Detect Device (mobile,tablet,desktop,bot)
 - Detect Operating System
 - User Host
 - User IP
 - Detect ISP (UK Only)
 - inludes geoip fuctions (php_goip_exstention installed on server)
 
 ## Usage 
 
 $UA = new UserAgent;
 echo $UA->IP(); // returns IP
 if($UA->isMobile()){
  // if is mobile
 }else{
  // if is not mobile
 }
