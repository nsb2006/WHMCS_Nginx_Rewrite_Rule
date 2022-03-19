Nginx rewrite rule for WHMCS, tested on version 7.10.2.

To get started, imagine your website configuration file located here:
_conf/vhost/yourdomain.conf_

Download the whmcs.conf file and save to _conf/rewrite/whmcs.conf_, then include the rewrite file in your configuration file:

server {
  ...
  include  rewrite/whmcs.conf;
  }

