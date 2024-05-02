# java

## history && select
https://whichjdk.com/
https://en.wikipedia.org/wiki/Java_version_history


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
```


## microsft 
https://www.microsoft.com/openjdk



# openjdk lts support time
https://endoflife.date/oracle-jdk
https://access.redhat.com/articles/1299013
https://www.oracle.com/java/technologies/java-se-support-roadmap.html
https://adoptium.net/support/
https://www.azul.com/products/azul-support-roadmap/

