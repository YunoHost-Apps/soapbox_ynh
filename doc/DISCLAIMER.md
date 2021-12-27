### Important points to read before installing

- [Pleroma (Yunohost ver.)](https://github.com/YunoHost-Apps/pleroma_ynh) must be installed locally before you install SoapboxFE
- SoapboxFE must be installed under a Pleroma domain (i.e soapboxfe.your-pleroma-instance-domain.net)
- AdminFE under SoapboxFE returns 404

Using screen in case of disconnects

``` 
sudo apt-get install screen
screen
sudo yunohost app install https://github.com/YunoHost-Apps/soapbox_ynh.git
```
Recover after disconnect:
```
screen -d
screen -r
```
