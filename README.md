All these files are one-unzip to install, you dont need to know where to put the files, just unzip and restart server

# How to use these zip files?

This is a bash script example with rehlds-3.7.0.694.zip file

```sh
# Go to your HLDS server directory
cd /path/to/hlds-server/

# Download zip file
wget https://github.com/leobrines/base-files-cs-1.6/raw/master/rehlds-3.7.0.694.zip

# Unzip file
unzip rehlds-3.7.0.694.zip
```

Ready, now you have rehlds installed!

# How to install sma plugins?

This is a bash script example with anticheats-amx.zip file

```sh
# Download and unzip zip file

cd /path/to/hlds-server/
wget https://github.com/leobrines/base-files-cs-1.6/raw/master/anticheats-amx.zip
unzip anticheats-amx.zip

# Go to scripting AMXX directory

cd /path/to/server/cstrike/addons/amxmodx/scripting/

# Enable execution of amxxpc and amxxpc.so

chmod +x amxxpc*

# Start to compile

./amxxpc antinoflash.sma
./amxxpc filescheck.sma

# Move your compiled files to "plugins" folders

mv *.amxx ../plugins/
```

Ready, you have Anticheat plugins installed on your server
