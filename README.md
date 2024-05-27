FAZENDO DOWNLOAD DO INSTALADOR & INICIANDO A PRIMEIRA INSTALAÇÃO (USAR SOMENTE PARA PRIMEIRA INSTALAÇÃO):

```bash
sudo apt install -y git && git clone https://github.com/psyberweb/installwhaticket.git && sudo chmod -R 777 installwhaticket && cd installwhaticket && sudo ./install_primaria
```

ACESSANDO DIRETORIO DO INSTALADOR & INICIANDO INSTALAÇÕES ADICIONAIS (USAR ESTE COMANDO PARA SEGUNDA OU MAIS INSTALAÇÃO:
```bash
cd && rm -rf instalodordeploy && git clone https://github.com/psyberweb/installwhaticket.git && sudo chmod -R 777 installwhaticket && cd installwhaticket && sudo ./install_instancia
```

