## Installation 
En Arch Linux rxfetch esta disponible en AUR, puedes instalarlo:
``` yay -S rxfetch```

O puedes clonarlo y ejecutarlo:
```
git clone https://github.com/mangeshrex/rxfetch
cd rxfetch
cp ttf-material-design-fonts/* $HOME/.local/share/fonts
fc-cache -fv
./rxfetch
```
Si ya tienes las fuentes instaladas, ejecuta esto:
```
wget https://raw.githubusercontent.com/Mangeshrex/rxfetch/main/rxfetch && chmod +x rxfetch
./rxfetch
```
Puedes añadir rxfetch al PATH reemplazando por /usr/bin
```
sudo cp rxfetch /usr/bin
```
