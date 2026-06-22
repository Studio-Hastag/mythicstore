# MythicStore

The official Software Manager of MythicOS. 

![image](https://user-images.githubusercontent.com/19881231/122644976-86767180-d120-11eb-9cf4-eed2813f749b.png)

## Build
```bash
git clone https://github.com/Studio-Hastag/mythicstore.git
cd mythicstore
sudo apt build-dep .
dpkg-buildpackage --no-sign
```
# Install
```bash
cd ..
sudo dpkg -i mythicstore*.deb
```
