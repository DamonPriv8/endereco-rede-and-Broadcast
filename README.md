# Descobrir Endereço de Rede and Endereço Broadcast

Olá, me chamo Damon. 👋
Tenho 17 anos, atualmente estou estudando redes! 📡

Irei ensinar a vocês nesse repositório como descobrir o endereço de rede e o endereço broadcast.

Endereço de rede é o endereço que define qual a rede que o computador está conectado.

Endereço de Broadcast é o endereço utilizado para comunicar com todas as máquinas de uma determinada rede. Ele é sempre o último endereço na rede.

Vou botar um endereço de IP e uma máscara de rede como exemplo abaixo:
**IP** : 192.168.0.9
**Máscara de Rede** : 255.255.255.0

O 255 é = (igual) a (REDE) **||**
O 0 (zero) é = (igual) a (HOST) mais simplicado (computador/máquina conectada na rede)

**1)** Passo para descobrir Endereço de Rede.

- Recortar 255 da máscara de rede.

Cortando ele ficará .0

2) Inserir o valor do endereço IP que está logo acima no exemplo referente ao intervalo após recortar a máscara.

- 192.168.0.0 = Endereço de Rede


Logo abaixo, vamos descobrir o endereço de Broadcast 👇🏻

**1) Passo** para descobrir o Endereço de Broadcast

- Pegar o endereço de rede e recortar os "0" (zero) originais da máscara de rede.

**Endereço de Rede** = 192.168.0.0
**Endereço de Rede recortado** = 192.168.0. (repare que foi recortado só o 0 original)

2) Pegar o intervalo e inserir "255" nos espaços que foram recortados.

- 192.168.0.255 = **__Endereço de Broadcast__**
