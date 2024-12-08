# Phishing para captura de senhas de Login 🕹
Ferramenta para capturar dados com Engenharia Social utilizando Setoolkit 
O SEToolkit (Social-Engineer Toolkit) é uma ferramenta poderosa e amplamente usada no Kali Linux para realizar testes de penetração focados em engenharia social. Ela é projetada para automatizar ataques de engenharia social, como phishing, coleta de informações e exploits baseados em interações humanas.

## Ferramentas Necessárias 🛠
- Kali Linux
  ```
  https://www.kali.org/get-kali/#kali-platforms
  ```
- Kit de ferramentas de configuração
  ```
  sudo apt-get update && sudo apt-get upgrade && sudo apt-get dist-upgrade 
  ```
## Configurando o Phishing no Kali Linux 📋
- Acesso root:sudo su
- Iniciando o setoolkit no terminal: setoolkit

## Passo a Passo 📊
1- Tipo de ataque: Social-Engineering Attacks

2- Vetor de ataque:Web Site Attack Vectors

3- Método de ataque:Credential Harvester Attack Method 

4- Método de ataque: Web Templates
 ```
   1) Web Templates
   2) Site Cloner
   3) Custom Import
```


5- Obtendo o seu endereço da máquina:ifconfig

6- Selecione: Google
```
    1. Java Required
    2. Google
    3. Twitter
```

 
 Criando servidor...
   ```
         set:webattack> Select a template: 2
      
      [*] Cloning the website: http://www.google.com                          
      [*] This could take a little bit...                                     
      
      The best way to use this attack is if username and password form fields 
      [*] The Social-Engineer Toolkit Credential Harvester Attack
      [*] Credential Harvester is running on port 80                          
      [*] Information will be displayed to you as it arrives below:           
      ^C[*] File in XML format exported to /root/.set/reports/2024-12-08 09:46:12.444060.xml for your reading pleasure...                             
      

  ```
## Site criado no IP utilizado ✅

- Exemplo 192.168.1.0
```
  set:webattack> IP address for the POST back in Harvester/Tabnabbing [192.168.1.10]:
```
## Utilização do Template Google 
Após a vítima se conectar ao site phishing, ela irá se deparar com a Tela de Login, após se conectar automaticamente será redirecionada para a pagina do Google, como se o login tivesse funcionado. 

![tela](https://github.com/user-attachments/assets/fd493b8a-bdfd-407f-9a4f-1f141f70a006)

## Redirecionamento
![fake](https://github.com/user-attachments/assets/137eb1dc-5dc0-49cf-b53c-5e3a58f1258c)

## Resultado na tela do Atacante ☠️
![resultado](https://github.com/user-attachments/assets/d0a4e3d3-4025-45a9-9706-662a44c17cf9)




