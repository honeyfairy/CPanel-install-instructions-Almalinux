# CPanel-install-instructions-Almalinux
 do manual partitioning, make root 10gb and /home the rest of space, other two leave as default.
 
 set static ip, set hostname if you have one.
 set time and root pw
 
 Currently there is an issue with the mysql key, so BEFORE install first run this:!
 
 rpm --import https://repo.mysql.com/RPM-GPG-KEY-mysql-2022

Then run
cd /home && curl -o latest -L https://securedownloads.cpanel.net/latest && sh latest



https://support.cpanel.net/hc/en-us/articles/4419382481815-MySQL-GPG-keys-expired-preventing-installation-upgrade-of-MySQL-packages-from-the-official-repository-?_ga=2.173503331.1792254924.1659046436-1811324534.1657406511

