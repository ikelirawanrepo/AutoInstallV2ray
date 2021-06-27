# AutoInstallV2ray
Debian 9 &amp; 10 Ubuntu 18.04 &amp; 20.04  

*Step 1*

apt update &amp;&amp; apt upgrade -y &amp;&amp; update-grub &amp;&amp; sleep 2 &amp;&amp; reboot  

*Step 2 *

sysctl -w net.ipv6.conf.all.disable_ipv6=1 &amp;&amp; sysctl -w net.ipv6.conf.default.disable_ipv6=1 &amp;&amp; apt update &amp;&amp; apt install -y bzip2 gzip coreutils screen curl &amp;&amp; wget https://github.com/ikelirawanrepo/AutoInstallV2ray/raw/main/setup.sh &amp;&amp; chmod +x setup.sh &amp;&amp; screen -S setup ./setup.sh
