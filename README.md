# Find any wifi password
Wifi passwords on your machine are stocked, do you want to see them ?
Yes , ok !

first type:

```PY
color a 
cls
``` 
(only for style)

then type :

```PY
netsh wlan show profiles 
```

then select a profile and type 

```PY
netsh wlan show profil PORFILE_NAME key=clear 
```

here we go, work done !


code & tips by [natrixdev](https://github.com/natrixdev)

