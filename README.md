# script
# Order License
# t.me/whytzy96


* apt update && apt upgrade -y && update-grub && sleep 2 && reboot

* rm -f setup.sh && sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt-get update -y && apt-get upgrade -y && apt install screen zip ftp bzip2 sudo gzip coreutils wget curl neofetch figlet -y && wget https://raw.githubusercontent.com/aowkwowkwok/script/main/setup.sh && chmod +x setup.sh && screen -S setup.sh ./setup.sh
