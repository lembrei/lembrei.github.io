---
title: Instalação do Wireshark
author: Pa3r1ck
date: 2023-02-26 20:10:00 +0800
categories: [Wireshark, Tutorial, Linux, Segurança]
tags: [linux, wireshark]
pin: true
---


# Instalação do Wireshark no Linux

## Instalação do Wireshark no Linux de forma a exexecutar o programa como um usúario comum.

### Para tal é necessário executar alguns comandos de forma a ajustar as premições necessárias.

A primeira coisa a fazer é naturalmente instalar o prorama com o seguinte comando.

``` bash
sudo apt install wireshark
```
De seguida criamos um grupo chamado Wireshark.

```
sudo groupadd wireshark
```
Adicionamos o nosso nome de utilizador ao grupo que acababos de criar. Neste exemplo o utilizador dá pelo nome de "user".

```
sudo adduser user wireshark
```
Fazemos a alteração do grupo.

```
sudo chgrp wireshark /usr/bin/dumpcap
```

Alteramos as permições.

```
sudo chmod 750 /usr/bin/dumpcap
```

E por fim emitimos o seguinte comando.

```
sudo setcap cap_net_raw,cap_net_admin=eip /usr/bin/dumpcap
```

No final da emição destes comandos acima descritos é necessário reniciar o sistema operativo de forma a que as alterações sejam postas em prática.
