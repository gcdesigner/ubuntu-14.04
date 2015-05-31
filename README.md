# ubuntu-14.04
Configuracoes para instalacao DELL Inspiron E1505

- Update dos pacotes<br>
<code>sudo apt-get update</code>
<br>

- Wirelles - Broadcom BCM4311<br>
<code>sudo apt-get purge bcmwl-kernel-source broadcom-sta-common broadcom-sta-source</code><br>
<code>sudo apt-get install b43-fwcutter firmware-b43-installer</code><br>
<p>https://help.ubuntu.com/community/WifiDocs/Driver/bcm43xx?action=show&redirect=BroadcomSTA%28Wireless%29</p>
