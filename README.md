# ubuntu-14.04
Configuracoes para instalacao DELL Inspiron E1505

- Update dos pacotes<br>
<code>sudo apt-get update</code>
<br>

- Wirelles - Broadcom BCM4311<br>
<code>sudo apt-get purge bcmwl-kernel-source broadcom-sta-common broadcom-sta-source</code><br>
<code>sudo apt-get install b43-fwcutter firmware-b43-installer</code><br>
<p>https://help.ubuntu.com/community/WifiDocs/Driver/bcm43xx?action=show&redirect=BroadcomSTA%28Wireless%29</p>

<br>

- Apache
<code>sudo apt-get install apache2</code>
<br>

- MySQL
<code>sudo apt-get install mysql-server mysql-common mysql-client</code>
<br>

- PHP
<code>sudo apt-get install php5</code>
<br>

- Libs
<code>sudo apt-get install libapache2-mod-auth-mysql php5-mysql</code>
<br>

- Phpmyadmin
<code>sudo apt-get install phpmyadmin</code>
<br>

- Permissao da pasta
<code>chmod 777 /var/www/</code><br>
<code>chmod 777 /var/www/index.html</code><br>
<code>chmod 777 /etc/php5/apache2/php.ini</code>
<br>

-Charset UTF8
<code>sudo nano /etc/php5/apache2/php.ini</code><br>
<code>ctrl+w = pesquisar: default_charset</code>
<code>descomentar = default_charset = "UTF-8"</code>
<br>
