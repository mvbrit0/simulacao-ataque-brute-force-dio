# 📘 Desafio DIO: Simulando um Ataque de Brute Force de Senhas com Medusa e Kali Linux
## 📝 Descrição do desafio
Este desafio da DIO tem como objetivo simular um ataque de força bruta, em um ambiente controlado com VMs e em serviços vulneráveis (FTP, DVWA e SMB) utilizando Kali Linux e a ferramenta Medusa para propor e exercitar medidas de prevenção.
## ⚙️ Configuração do Ambiente
| Software | Versão | Link |
|----------|------|------|
| Kali Linux | 2025.3  | https://www.kali.org/get-kali/#kali-virtual-machines |
| Metasploitable | 2.0.0 | https://sourceforge.net/projects/metasploitable/files/Metasploitable2/ |
| Oracle VirtualBox  | 7.2.4  | https://www.virtualbox.org/wiki/Downloads |
### Rede
1. VirtualBox Host-Only Metasploitable ![Clique para ver execução](images/configuracao-rede-meta-vb.PNG)
2. VirtualBox Host-Only Kali Linux ![Clique para ver execução](images/configuracao-rede-kali-linux-vb.PNG)
### Validação
Conectividade comando ping -c ![Clique para ver execução](images/validacao-conexao-kali-meta-vb.PNG)
## 🔐 Cenários de Ataque
### Força Bruta em FTP
