
FROM joomla:3

RUN apt-get update; apt-get -y install \
php5-curl php5-mcrypt php5-xml; \
rm -rf /var/lib/apt/lists/*; \
docker-php-ext-install fileinfo gd iconv json mbstring zip;

# Availible exts: bcmath bz2 calendar ctype curl dba dom enchant exif fileinfo filter ftp gd gettext gmp hash iconv imap interbase intl json ldap mbstring mcrypt mssql mysql mysqli oci8 odbc opcache pcntl pdo pdo_dblib pdo_firebird pdo_mysql pdo_oci pdo_odbc pdo_pgsql pdo_sqlite pgsql phar posix pspell readline recode reflection session shmop simplexml snmp soap sockets spl standard sybase_ct sysvmsg sysvsem sysvshm tidy tokenizer wddx xml xmlreader xmlrpc xmlwriter xsl zip

