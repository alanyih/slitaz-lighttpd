# slitaz-lighttpd

##LightTPD Web Server
http://doc.slitaz.org/en:handbook:webserver

##About LightTPD
	This chapter describes the configuration and use of the LightTPD web server. 	
	It's a fast, secure, flexible HTTP server, using a small memory footprint. 
	It enables intelligent management of the cpu load and offers FastCGI support, 
	CGI, Auth, Output compression and the rewriting of URLs, etc. LightTPD is a 
	cheap way to host your own site on an old machine.
LightTPD website: http://www.lighttpd.net/

##/var/www - Root directory of documents
	The /var/www folder is the root directory of documents - you can access this 
	via the URL http://localhost/. If you want to host a site, you can save all 
	your documents in here. If you want to host multiple sites, you'll need to 
	create virtual hosts. 
	Note you can also check the http://localhost/server-status.

##/etc/lighttpd/lighttpd.conf - LightTPD configuration file
	The main configuration file for LightTPD (lighttpd.conf) is located in /etc/lighttpd/. 
	This file provided by SliTaz is self-explanatory, just browse. You can find other 
	examples on the LightTPD website. On SliTaz you'll also find a vhosts.conf file for 
	the configuration of any virtual hosts (hosting several sites on the same server).
