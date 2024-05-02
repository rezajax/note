# install idea

## ch
``` bash
unzip -x jetbra*

sudo mv jetbra /opt

sh /opt/jetbra/scripts/install.sh
```

## install
https://www.jetbrains.com/help/idea/installation-guide.html#standalone

```bash
sudo tar -xzf ideaIU-*.tar.gz -C /opt
sudo mv /opt/idea* /opt/idea
```

### create shortcut
tools -> create desktop entery

### cli command (idea)
tools -> configuring command-line lancher

https://www.jetbrains.com/help/idea/2024.1/working-with-the-ide-features-from-command-line.html?Working_with_the_IDE_Features_from_Command_Line&utm_source=product&utm_medium=link&utm_campaign=IU&utm_content=2024.1#standalone

```bash
sudo ln -s /opt/idea/bin/idea.sh /usr/local/bin/idea
```


