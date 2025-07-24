# Phishing para captura de senhas do Facebook

### Usei as ferramentas

- Kali Linux em VM bridge na rede;
- setoolkit

### Configurando o Phishing no Kali Linux

- Acesso root: ``` sudo su ```
(Usei apenas su e mudei pra root)
- Iniciando o setoolkit: ``` setoolkit ```
- Tipo de ataque: ``` Social-Engineering Attacks ```
- Vetor de ataque: ``` Web Site Attack Vectors ```
- Método de ataque: ```Credential Harvester Attack Method ```
- Método de ataque: ``` Site Cloner ```
- Obtendo o endereço da máquina: ``` ifconfig ```
- URL para clone: http://www.facebook.com

### Resutados
No arquivo report.xml (Dados fake)
As primeiras capturas fiz via terminal (Putty), como n�o deu muito certo alguns
comandos fiz as finais de dentro da VM no shell do gnome, na m�quina do Kali.
![Alt text](./passwd.png "Optional title")
