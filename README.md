**ESTE ES UN TUTORIAL PARA HACER UN ACCESO DE ANACONDA EN UBUNTU.**


##### Iniciamos en la terminal escribiendo lo siguiente:

```bash
gedit ~/.local/share/applications/anaconda.desktop
```
###### gedit es un editor de texto podrías usar nano o vim.

##### Una vez abierto el editor vaciaremos la información al siguiente formato.
```bash
[Desktop Entry]
Type=Application
Name=ElNombreQueQuieras
Exec=/La Path Para Ejecutar
Icon=/La Path De Tu Icono
Terminal=false
```

```bash
[Desktop Entry]
Type=Application
Name=Anaconda
Exec=/home/nemubuntu/anaconda3/bin/anaconda-navigator
Icon=/home/nemubuntu/anaconda3/lib/python3.9/site-packages/anaconda_navigator/app/icons/Icon1024.png
Terminal=false
```
###### En mi caso es así la path, cada quien debe poner la suya.

##### Lo guardas y ya esta listo.

### Claro también puedes ir a la PATH del archivo y tipear ./ antes en este caso de anaconda-navigator
###### ./anaconda-navigator
##### Pero tenía ganas de hacer un acceso en ubuntu n__n
![imagen](https://github.com/AnabelBerumen/launcher_anaconda/blob/main/gnome-shell-screenshot-cuowd6.png?raw=true "imagen")



