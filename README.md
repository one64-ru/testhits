sudo -y update || apt update && sudo -y install git whiptail || apt install -y git whiptail && cd /root && git clone https://github.com/one64-ru/testhits.git && chmod -R 777 testhits && testhits/install.sh "2" "f51a97a304263e242216f22cf900060f" "10" "1" "1" "http://proxyserver.com/index.php"