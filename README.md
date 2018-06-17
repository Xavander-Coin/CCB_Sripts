# Installation guide for running the CCB VPS script
# Step 1
  * This will download the auto install script to your VPS.
```    
wget https://raw.githubusercontent.com/MotoAcidic/CCB_Sripts/master/CCB_install.sh

```
# Step 2
  * This will mount the script 
```
chmod 775 CCB_install.sh

```
# Step 3
  * This installs the script
```
./CCB_install.sh

```
# Step 4
  * Watch the block number until it gets to the current block height
```
watch cryptocashback-cli getinfo

```

# Step 5
  * Install upstart so you can use systemctl commands
```    
apt install upstart

```
# Step 6
  * These are the commands you are able to use
```    
systemctl start CryptoCashBack.service

systemctl status CryptoCashBack.service

systemctl stop CryptoCashBack.service

```
