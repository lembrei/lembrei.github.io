---
title: Instalação e uso do nmap 
author: pa3r1ck
date: 2023-03-12 21:10:00 +0800
categories: [nmap]
tags: [nmap]
pin: false
---

![image](https://camo.githubusercontent.com/2502e407355cd4180a1c66f1d93c744db982fc70e0504db04e2090afac7760fb/68747470733a2f2f692e6962622e636f2f4e54796e6472462f702d6e6d61702e706e67)



Nmap é uma ferramenta de código aberto amplamente utilizada para escanear e mapear redes. É uma das ferramentas mais populares entre os profissionais de segurança e administradores de sistemas, e pode ser usada para identificar vulnerabilidades em redes e sistemas.

Se você é um usuário do sistema operacional Ubuntu, instalar o Nmap é fácil. Basta abrir o terminal e digitar o seguinte comando:
``` bash
sudo apt-get install nmap
```
Isso irá instalar o Nmap no seu sistema. Depois de instalado, você pode começar a explorar as funcionalidades do Nmap.

Aqui estão cinco exemplos de como você pode usar o Nmap:

Escanear portas em um sistema: O Nmap pode ser usado para escanear portas em um sistema. Isso ajuda a identificar quais portas estão abertas e podem ser usadas para acesso não autorizado. Para escanear portas em um sistema, basta digitar o seguinte comando no terminal:
``` bash
nmap <endereço IP>
```
Substitua "endereço IP" pelo endereço IP do sistema que deseja escanear.

Descobrir dispositivos em uma rede: O Nmap pode ser usado para descobrir dispositivos em uma rede. Isso pode ser útil para identificar quais dispositivos estão conectados à sua rede. Para descobrir dispositivos em uma rede, basta digitar o seguinte comando no terminal:
``` bash
nmap -sP <endereço IP>/24
```
Substitua "endereço IP" pelo endereço IP da sua rede.

Descobrir o sistema operacional em um sistema: O Nmap pode ser usado para descobrir o sistema operacional em um sistema. Isso pode ser útil para identificar quais sistemas operacionais estão sendo usados em uma rede. Para descobrir o sistema operacional em um sistema, basta digitar o seguinte comando no terminal:
``` bash
nmap -O <endereço IP>
```
Substitua "endereço IP" pelo endereço IP do sistema que deseja escanear.

Escanear vulnerabilidades em um sistema: O Nmap pode ser usado para escanear vulnerabilidades em um sistema. Isso pode ajudar a identificar quais sistemas estão em risco de serem explorados por hackers. Para escanear vulnerabilidades em um sistema, basta digitar o seguinte comando no terminal:
``` bash
nmap -sV --script vuln <endereço IP>
```
Substitua "endereço IP" pelo endereço IP do sistema que deseja escanear.

Escanear uma rede Wi-Fi: O Nmap também pode ser usado para escanear uma rede Wi-Fi. Isso pode ajudar a identificar quais dispositivos estão conectados à sua rede Wi-Fi e se há dispositivos não autorizados. Para escanear uma rede Wi-Fi, basta digitar o seguinte comando no terminal:
``` bash
sudo nmap -sS <endereço IP>/24
```
Substitua "endereço IP" pelo endereço IP da sua rede Wi-Fi.

Em conclusão, o Nmap é uma ferramenta extremamente útil para administradores de rede e segurança. Se você é novo no uso do Nmap, comece experimentando esses exemplos e descubra como o Nmap pode ajudar a proteger sua rede e sistemas contra ameaças externas.