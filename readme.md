# Get started with linux OS

Basic packages for linux.

## Repositories
```
sudo add-apt-repository "deb http://archive.ubuntu.com/ubuntu $(lsb_release -sc) main universe restricted multiverse"
```
## Packages
* [redshift](https://github.com/jonls/redshift)
* sh
```
sudo apt install sh
```
* [ohmyzsh](https://ohmyz.sh/)
* [p10k](https://github.com/romkatv/powerlevel10k)
* [git](https://git-scm.com/)
```
sudo apt install git
```
* [snapd](https://snapcraft.io/store)
```
sudo apt install snapd
```
* [vscode](https://code.visualstudio.com/) via snap
```
sudo snap install --classic code
```
* [tmux](https://github.com/tmux/tmux/wiki)
```bash
sudo apt install tmux
```
* [nvm](https://github.com/nvm-sh/nvm)
* [lattedock](https://github.com/KDE/latte-dock)
* Apache2 server
```
sudo apt install apache2
```
* Php and complements 
```
sudo apt install php libapache2-mod-php php-mysql
```
* Mysql
```
sudo apt install mysql-server
```
To set mysql password follow this commands:

```mysql
select user, authentication_string, plugin, host from mysql.user;

alter user  'root'@'localhost' identified with  mysql_native_password by 'password';

flush privileges;

select user, authentication_string, plugin, host from mysql.user;
```
* [spotify](https://www.spotify.com/us/download/linux/)