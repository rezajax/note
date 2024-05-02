# java

## history && select
https://whichjdk.com/
https://en.wikipedia.org/wiki/Java_version_history
https://aws.amazon.com/corretto/faqs/#support_calendar


## oracle 
https://www.oracle.com/java/
https://www.java.com/en/
https://dev.java/
https://jdk.java.net/


## openJdk
https://openjdk.java.net/


## Adoptium eclipse (microsoft support it)
https://adoptium.net/temurin/releases/

### install 
```
# Ensure the necessary packages are present:
apt install -y wget apt-transport-https gpg
wget -qO - https://packages.adoptium.net/artifactory/api/gpg/key/public | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/adoptium.gpg > /dev/null
echo "deb https://packages.adoptium.net/artifactory/deb $(awk -F= '/^VERSION_CODENAME/{print$2}' /etc/os-release) main" | tee /etc/apt/sources.list.d/adoptium.list

sudo apt install temurin-21-jdk
```


## amazon corretto

### install

https://docs.aws.amazon.com/corretto/latest/corretto-11-ug/generic-linux-install.html
```bash
wget -O - https://apt.corretto.aws/corretto.key | sudo gpg --dearmor -o /usr/share/keyrings/corretto-keyring.gpg && \
echo "deb [signed-by=/usr/share/keyrings/corretto-keyring.gpg] https://apt.corretto.aws stable main" | sudo tee /etc/apt/sources.list.d/corretto.list

sudo apt-get update; sudo apt-get install -y java-11-amazon-corretto-jdk
```



## microsft 
https://www.microsoft.com/openjdk



# openjdk lts support time
https://endoflife.date/oracle-jdk
https://access.redhat.com/articles/1299013
https://www.oracle.com/java/technologies/java-se-support-roadmap.html
https://adoptium.net/support/
https://www.azul.com/products/azul-support-roadmap/



# Alternatives (Configure the default version)
sudo update-alternatives --config java
sudo update-alternatives --config javac