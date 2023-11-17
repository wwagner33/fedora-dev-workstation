# Preparando o Fedora para ser uma Estação de Trabalho para Desenvolvimento de Software
## Pacotes voltados ao desenvolvimento
```sh
sudo dnf -y groupinstall "Development Tools"
```

## Instalação da Linguagem Go

```sh
sudo dnf -y install golang
```

## Instalação da Linguagem Rust

```sh
sudo dnf -y install rust
```

## Instalando o ASDF
```sh
git clone https://github.com/asdf-vm/asdf.git ~/.asdf --branch v0.13.1
```
