# 📘 Desafio DIO: Simulando um Ataque de Brute Force de Senhas com Medusa e Kali Linux
## 📝 Descrição do desafio
Este desafio da DIO tem como objetivo simular um ataque de força bruta em um ambiente controlado com VMs, explorando serviços vulneráveis (FTP, DVWA e SMB). A execução utiliza o Kali Linux e a ferramenta Medusa, com a finalidade de propor e praticar medidas de prevenção.
## ⚙️ Configuração do Ambiente
| Software | Versão | Link |
|----------|------|------|
| Kali Linux | 2025.3  | https://www.kali.org/get-kali/#kali-virtual-machines |
| Metasploitable | 2.0.0 | https://sourceforge.net/projects/metasploitable/files/Metasploitable2/ |
| Oracle VirtualBox  | 7.2.4  | https://www.virtualbox.org/wiki/Downloads |
### Rede
1. VirtualBox Host-Only Metasploitable
![Clique para ver execução](images/configuracao-rede-meta-vb.PNG)
2. VirtualBox Host-Only Kali Linux
![Clique para ver execução](images/configuracao-rede-kali-linux-vb.PNG)
### Validação
#### Teste de Conectividade 
ping -c 
![Clique para ver execução](images/validacao-conexao-kali-meta-vb.PNG)
## 🔐 Cenários de Ataque
### Força Bruta em FTP
#### 1. Varredura de portas vulneráveis e versão dos serviços 
nmpa -sV -p 

![Clique para ver execução](images/comando-nmap-kali-vb.PNG)
#### 2. Teste de conectividade
ftp 
![Clique para ver execução](images/teste-conectividade-ftp-kali-vb.PNG)
#### 3. Criação de usuários e senhas
echo -e
![Clique para ver execução](images/criacao-user-pass-kali-vb.PNG)
#### 4. Força bruta em FTP
medusa -h
![Clique para ver execução](images/ataque-forca-bruta-medusa-ftp-vb.PNG)
