# mkvh
A tool for creating apache virtualhosts easily
# How to install
sudo su -
apt-get update
apt-get install -y git
git clone https://github.com/roybhaskar9/mkvh.git
chmod +x mkvh/*
cp mkvh/* /usr/bin
# How to create new virtual host for domain example.com
mkvh example.com
# How to list and see all virtual hosts on the system
