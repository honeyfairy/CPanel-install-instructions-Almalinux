# CPanel-install-instructions-Almalinux
 do manual partitioning, make root 10gb and /home the rest of space, other two leave as default.
 
 set static ip, set hostname if you have one.
 set time and root pw
 
 Currently there is an issue with the mysql key, so BEFORE install first run this:!
 
 rpm --import https://repo.mysql.com/RPM-GPG-KEY-mysql-2022

Then run
cd /home && curl -o latest -L https://securedownloads.cpanel.net/latest && sh latest
