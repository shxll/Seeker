O conceito por trás do Seeker é simples, assim como hospedamos páginas de phishing para obter credenciais, por que não hospedar uma página falsa que solicita sua localização, como muitos sites populares baseados em localização. O Seeker hospeda um site falso que pede permissão de localização e, se o alvo permitir, nós pode obter :

 Longitude
 Latitude
 Precisão
 Altitude - Nem sempre disponível
 Direção - Disponível apenas se o usuário estiver em movimento
 Velocidade - Disponível apenas se o usuário estiver em movimento

Junto com as informações de localização, também obtemos informações do dispositivo sem quaisquer permissões:

 ID exclusivo usando impressão digital em tela
 Modelo do dispositivo – nem sempre disponível
 Sistema operacional
 Plataforma
 Número de núcleos de CPU – resultados aproximados
 Quantidade de RAM - Resultados Aproximados
 Resolução da tela
 Informações da GPU
 Nome e versão do navegador
 Endereço IP público
 Endereço IP local
 Porto local

O reconhecimento automático de endereço IP é executado após o recebimento das informações acima.
## Instalação

### Kali Linux / Ubuntu / Termux

```bash
sudo apt install git
git clone https://github.com/shxll/Seeker.git
cd Seeker/ 
chmod +x install.sh 
./install.sh 
```

### Uso
```bash
python3 seeker.py
# problema com depência ou permissão rode no root do terminal.
```
### Melhor forma de usar ferramenta 

### Cria uma python venv:
```bash
sudo apt install python3-venv
```

### Criar uma venv:
```bash
python3 -m venv python3-venv
source python3-venv/bin/activate
# deactivate para desativar a venv
``` 

### Entre no diretório
```bash
cd Seeker/
python3 seeker.py
# problema de permissão ou dependência rode no root do terminal
sudo su
# senha do root
python3 seeker.py
```

### Interface
<p align = "center">
  <img src = "https://raw.githubusercontent.com/shxll/Seeker/main/Image/seeker.png">
</p>

### BOM PROVEITO!

# Redes Sociais
[Facebook](https://www.facebook.com/Shall777)
[Twitter](https://twitter.com/sharllanp)
[Linkedin](https://br.linkedin.com/in/sharllan-paulino)
[Whatsapp](https://wa.me/+5592981325925)

chave pix caso queira contribuir:
```bash
sharllans2@gmail.com
```
### Nome: Sharllan Paulino.
### PicPay.
