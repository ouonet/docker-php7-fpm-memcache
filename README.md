# docker-php7-fpm-memcache
  Although php offical image has provided docker-php-ext-installer to help user install php extension, we still need to build some extension by ourself, because it hasn't include all extensions,such like memcache.
# Base 
  php:7-fpm
  
# Memcache Source
  I use [https://github.com/websupport-sk/pecl-memcache/archive/php7.zip](https://github.com/websupport-sk/pecl-memcache/archive/php7.zip) to build memcache for php7

# All enabled extensions:

	[PHP Modules]
  	Core
  	ctype
  	curl
  	date
  	dom
	fileinfo
	filter
	gd
	hash
	iconv
	json
	ldap
	libxml
	mbstring
	mcrypt
	memcache
	mysqli
	mysqlnd
	openssl
	pcre
	PDO
	pdo_mysql
	pdo_sqlite
	Phar
	posix
	readline
	Reflection
	session
	SimpleXML
	SPL
	sqlite3
	standard
	tokenizer
	xml
	xmlreader
	xmlwriter
	zip
	zlib
	
	[Zend Modules]
# Other important information
see [https://hub.docker.com/_/php/](https://hub.docker.com/_/php/)
