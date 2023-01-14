# AssetsIndex
This repository is used to store minecraft 1.8's asset index for easy access. This is for personal use, feel free to take my scripts and change a few var names.


## Seperate folder

```
git clone https://github.com/lax1dude/eaglercraftx-1.8.git; cd ./eaglercraftx-1.8/mcp918; wget http://www.modcoderpack.com/files/mcp918.zip; wget https://launcher.mojang.com/v1/objects/0983f08be6a4e624f5d85689d1aca869ed99c738/client.jar; wget https://raw.githubusercontent.com/ThisIsALegitUsername/AssetsIndex/main/1.8.json; sudo apt-get install ffmpeg; cd ../; chmod +x ./build_init.sh; chmod +x ./build_make_workspace.sh; ./build_init.sh; ./build_make_workspace.sh
```

## Extract all sources into current dir

```
git clone https://github.com/lax1dude/eaglercraftx-1.8.git; mv -v ./eaglercraftx-1.8/* ./; cd mcp918; wget http://www.modcoderpack.com/files/mcp918.zip; wget https://launcher.mojang.com/v1/objects/0983f08be6a4e624f5d85689d1aca869ed99c738/client.jar; wget https://raw.githubusercontent.com/ThisIsALegitUsername/AssetsIndex/main/1.8.json; sudo apt-get install ffmpeg; cd ../; chmod +x ./build_init.sh; chmod +x ./build_make_workspace.sh; ./build_init.sh; ./build_make_workspace.sh
```

## Create new offline download

```
cd javascript; rm EaglercraftX_1.8_Offline_en_US.html; rm EaglercraftX_1.8_Offline_International.html; rm Resent_EaglercraftX_1.8_US.html; rm; Resent_EaglercraftX_1.8_International.html; cd ../; ./MakeOfflineDownload.sh; cd javascript; mv EaglercraftX_1.8_Offline_en_US.html Resent_EaglercraftX_1.8_US.html; mv EaglercraftX_1.8_Offline_International.html Resent_EaglercraftX_1.8_International.html;
```
