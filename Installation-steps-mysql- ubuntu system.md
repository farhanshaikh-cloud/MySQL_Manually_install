If you're using Ubuntu, then you should not download .rpm files. RPM packages are for RHEL, CentOS, Rocky Linux, AlmaLinux, and Amazon Linux.

For Ubuntu, you have two options:

Option 1: Install MySQL from Ubuntu Repositories (Recommended)
sudo apt update
sudo apt install mysql-server -y

Verify installation:

mysql --version

Check service status:

sudo systemctl status mysql
Option 2: Install Official MySQL Packages for Ubuntu

Download the MySQL APT repository package from:

MySQL Community Downloads

For Ubuntu, download a file similar to:

mysql-apt-config_x.x.x_all.deb

Then install it:

sudo dpkg -i mysql-apt-config_*.deb
sudo apt update
sudo apt install mysql-community-server -y
First, check your Ubuntu version

Run:

lsb_release -a

or

cat /etc/os-release

Example output:

Ubuntu 22.04 LTS

or

Ubuntu 24.04 LTS
