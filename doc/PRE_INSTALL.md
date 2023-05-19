## Important points to read before installing

1. **Glitch-Soc** require a dedicated **root domain**, eg. glitchsoc.domain.tld
1. You can't change the domain once installed.
1. The user choosen during the installation is automatically created in Glitch-Soc with admin rights
1. At the end of the installation a mail is sent to the user with the automatically generated password
1. It seems important to close the inscriptions for your Glitch-Soc, so that it remains a private body. We invite you to block remote malicious instances from the administration interface. You can also add text on your home page.

## Using *screen* in case of disconnect

```
$ sudo apt-get install screen
$ screen
$ sudo yunohost app install https://github.com/YunoHost-Apps/glitchsoc_ynh.git
```
Recover after disconnect:
```
$ screen -d
$ screen -r
```
