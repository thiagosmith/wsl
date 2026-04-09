# WSL Instalation
Definir a versão 2 do WSl
```
wsl --set-default-version 2
```
Verificar a instalação do WSL
```
Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Windows-Subsystem-Linux
```
Atualizar o WSL
```
wsl --update
```
Ajuda do WSL
```
wsl --help
```
Listar as ditros disponíveis
```
wsl --list --online
```
Instalar o Kali Linux
```
wsl --install -d kali-linux
```
Definir usuário e senha do Kali
```
Digita a o nome do usuário do kali.

Digite uma senha para o usuário e repete a senha.
```
Atualizar o Kali
```
sudo apt update && sudo apt upgrade -y
```
Instalar o Kex
```
sudo apt install kali-win-kex -y
```
Carregar o Kex
```
kex
```
Senha do Kex
```
password de 6 a 8 dígitos
```
Solicitar asenha ao carregar o kex
```
n
```
Realizar a instalação completa do Kali Linux
```
sudo apt-get install kali-linux-large -y
```
