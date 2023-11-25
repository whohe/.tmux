# Settings for Tmux - Configuraciones para Tmux

Tmux is a terminal multiplexer that allows multiple applications to be used simultaneously.

A lightweight alternative to using byobu on rpm or alpine linux systems where we do not have access to this repository.

### Features of Tmux 
* Multiple terminal sessions: Create and switch between multiple terminal sessions. 
* Windows and panes: Divide each terminal session into multiple windows and panes. 
* Session persistence: Save and restore terminal sessions. 
* Keybindings: Customize keybindings for tmux commands. 

Tmux es un multiplexor de terminal que permite utilizar varias aplicaciones de forma simultánea.

Una alternativa ligera al uso de byobu en sistemas rpm o alpine linux donde no tenemos acceso a este repositorio.

### Características de Tmux 

* Sesiones de terminal múltiples: Cree y cambie entre múltiples sesiones de terminal. 
* Ventanas y paneles: Divida cada sesión de terminal en múltiples ventanas y paneles. 
* Persistencia de sesión: Guarde y restaure sesiones de terminal. 
* Atajos de teclado: Personalice los atajos de teclado para los comandos de tmux. 

## Requirements - Requisitos
RPM based linux systems - sistemas linux basados en RPM

Use the package manager [dnf](https://docs.fedoraproject.org/es/quick-docs/dnf-vs-apt/) to install tmux and git.

```bash
dnf install tmux
dnf install git
dnf install fish
```

Alpine linux 

Use the package manager [apk](https://wiki.alpinelinux.org/wiki/Alpine_Package_Keeper) to install tmux and git.
```bash
apk add tmux
apk add git
apk add fish
```

Debian / Ubuntu - linux 

Use the package manager [apt](https://wiki.debian.org/es/Apt) to install tmux and git.

```bash
apt install tmux
apt install git
apt install fish
```

## Installation

We are going to clone this repository in the current user's folder, a non-root user is recommended

```bash
cd ~
git clone https://github.com/whohe/.tmux
ln -s .tmux/tmux.conf .tmux.conf
```

## Usage
Run the multiplexer by typing tmux in the console
```bash 
tmux
```
```bash 
Ctrl + <F2> - to open split screen vertically
Shift + <F2> - to open split screen horizontally
<F2> - Open a new window
```

```bash 
Shift + <Right> - jump to the right panel
Shift + <Left> - jump to the left panel
Shift + <Up> - jump to the top panel
Shift + <Down> - jump to the panel below
```

```bash 
Alt + <Right> - moves to the right window
Alt + <Left> - moves to the left window
```


![Preview](capture.png?raw=true "Preview")

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[GPL V3](https://www.gnu.org/licenses/gpl-3.0.html)
