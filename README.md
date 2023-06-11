# Vagrant Ubuntu
Este projeto tem como objetivo a criação de uma máquina virtual simples com o SO Ubuntu 22.04 usando o Vagrant.

## Configurações do projeto

O projeto contém o arquivo `Vagrantfile` - arquivo principal do Vagrant, onde estão definidas as configurações de RAM e CPU da máquina virtual (1 GB de RAM e 1 CPU). 

Também foram definidas as seguintes configurações de rede:
- redirecionamento de porta para a porta 8080;
- ip da máquina;
- uso da placa de rede do host em modo `bridge`.

## Como utilizar este repositório

1. Primeiro, você deve clonar este repositório com o comando: `git clone https://github.com/ludsilva/vagrant-ubuntu.git`

2. Para rodar este projeto localmente, você precisa ter o Vagrant instalado em sua máquina local. 
  - [Windows](https://www.youtube.com/watch?v=yFSm6TXBuDE&ab_channel=VemcomoPY) | [Linux](https://www.youtube.com/watch?v=fwKPiyWaDbU&pp=ygUQaW5zdGFsYXIgdmFncmFudA%3D%3D) | [Documentação do Vagrant](https://developer.hashicorp.com/vagrant/downloads)

3. Após instalado, siga com os seguintes comandos no terminal / bash dentro do repositório:
```
## Criar a instância
 vagrant up
## Acessar a instância via ssh
  vagrant ssh
```
