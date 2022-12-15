# Training-Devops

sudo apt-key adv --fetch-keys 'https://mariadb.org/mariadb_release_signing_key.asc'
sudo add-apt-repository 'deb [arch=amd64] http://mariadb.mirror.globo.tech/repo/10.5/ubuntu focal main'
apt update
apt remove mariadb-server
apt install mariadb-server
apt list --installed | grep mariadb-server
