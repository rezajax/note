# install Android studio
https://developer.android.com/studio/install

## install
If you are running a 64-bit version of Ubuntu, you need to install some 32-bit libraries with the following command:

preinstall
```bash
sudo apt-get install libc6:i386 libncurses5:i386 libstdc++6:i386 lib32z1 libbz2-1.0:i386
```

```bash
sudo tar -xvzf android-studio-2023.3.1.18-linux.tar.gz -C /opt
```

Unpack the .zip file you downloaded to an appropriate location for your applications, such as within /usr/local/ for your user profile or /opt/ for shared users.
```bash
sudo ln -s /opt/android-studio/bin/studio.sh /usr/local/bin/studio
```


## install


### create shortcut
tools -> create desktop entery

### cli command (idea)
tools -> configuring command-line lancher

https://www.jetbrains.com/help/idea/2024.1/working-with-the-ide-features-from-command-line.html?Working_with_the_IDE_Features_from_Command_Line&utm_source=product&utm_medium=link&utm_campaign=IU&utm_content=2024.1#standalone



