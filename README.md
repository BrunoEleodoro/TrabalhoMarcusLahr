# TrabalhoMarcusLahr

Command list used:

```
docker pull kalilinux/kali-rolling
docker run -t -d -i kalilinux/kali-rolling /bin/bash
apt-get update && apt-get install metasploit-framework
apt install python
apt install git
apt install dnsutils
git clone https://github.com/Pavithran-R/Hammer/
sudo apt-get install software-properties-common
sudo add-apt-repository ppa:deadsnakes/ppa
sudo apt-get update
sudo apt-get install python3.6
git clone https://github.com/XCHADXFAQ77X/XERXES.git
cd XERXES
gcc -o xerxes xerxes.c
./xerxes IP PORT
```
--- 

## Protegendo o Apache

    https://www.myrouter.com.br/protegendo-o-apache-contra-ataques-dos-e-slowloris/

---

## Formas de se prevenir contra ataques DDOS:

1- Faca um plano de resposta a incidente de DNS

    - Faca um checklist com todos os seus dispositivos na rede e ferramentas de filtro de pacotes de rede e mantenha essa lista atualizada.

    - Monte um time de resposta para lidar com esse ataque e garantir que eles estejam treinados para a hora do ataque.

    - Mantenha comunicacao com clientes e com os fornecedores de servicos em cloud para saber exatamente o que esta acontecendo.

2- Monte uma Infraestrutura segura

    Combine firewalls, VPN, anti-spam e filtro de conteudo, loadbalancers e outras camadas de protecao para DDoS, juntos eles permitem analise do trafego de rede e tambem a mitigacao desses ataques.

3- Monte uma Infraestrutura forte

    O ideal e ter mais de um servidor para sua aplicacao, assim tendo redundancia e aumentando a disponibilidade do seu servico, especialmente se for em localizacoes geograficas diferentes.




https://phoenixnap.com/blog/prevent-ddos-attacks