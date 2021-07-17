# VirtualDevWindows
VM de windows -> https://developer.microsoft.com/en-us/windows/downloads/virtual-machines/

## Instrucciones

#### Abrir una ventana de powershell como Administrador

```
PS > Set-ExecutionPolicy -ExecutionPolicy Unrestricted -Force
PS > . { Invoke-WebRequest -useb https://boxstarter.org/bootstrapper.ps1 } | iex; Get-Boxstarter -Force
```
#### Una vez que se haya completado la instalación, aparecerá un icono de Boxstarter Shell en su escritorio. Inicie Boxstarter Shell e ingrese el siguiente comando:

```
PS > Install-BoxstarterPackage -PackageName https://raw.githubusercontent.com/b4r0nd3l4b1rr4/VirtualDevWindows/main/VariacionRTO.choco
```
#### Se reiniciará la maquina windows y se instalará el script Choco.

#### Profit :)
