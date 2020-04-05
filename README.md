All these files are one-unzip to install, you dont need to know where to put rehlds files, just unzip and restart server

# How to use these zip files?
1. Go to your HLDS server directory

```sh
cd /path/to/hlds-server/
```

2. Download zip file

```sh
wget https://github.com/leobrines/base-files-cs-1.6/raw/master/rehlds-3.7.0.694.zip
```

3. Unzip file

```sh
unzip rehlds-3.7.0.694.zip
```

Ready, now you have rehlds installed!

# How to install sma plugins?
1. Download and unzip zip file. Example:

```sh
cd /path/to/hlds-server/
wget https://github.com/leobrines/base-files-cs-1.6/raw/master/anticheats-amx.zip
unzip anticheats-amx.zip
```

2. Go to scripting AMXX directory

```sh
cd /path/to/server/cstrike/addons/amxmodx/scripting/
```

3. Enable execution of amxxpc and amxxpc.so

```sh
chmod +x amxxpc*
```

4. Start to compile

```sh
./amxxpc antinoflash.sma
./amxxpc filescheck.sma
```

4. Move your compiled files to "plugins" folders

```sh
mv *.amxx ../plugins/
```

Ready, you have Anticheat plugins installed on your server
