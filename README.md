# Installation guide for running the CCB VPS script
# Step 1
  * This will download the auto install script to your VPS.
```    
wget -q https://github.com/CryptoCashBack/CryptoCashBack/releases/CryptoCashBack-Linux.tar.gz

```
# Step 2
  * This will mount the script 
```
chmod +x CCB_install.sh

```
# Step 3
  * This installs the script
```
./CCB_install.sh install

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
systemctl start CCB

systemctl status CCB

systemctl stop CCB

```
