# NAT (Network Address Translation)

NAT é uma técnica utilizada para traduzir endereços IP privados em endereços IP públicos.

Ele é amplamente utilizado em roteadores.

## Problema que o NAT resolve

Existe um número limitado de endereços IPv4 disponíveis na internet.

Para resolver isso, redes internas usam **endereços IP privados**.

Exemplo:

192.168.0.10

Quando um dispositivo acessa a internet, o NAT traduz esse endereço para um IP público.

## Funcionamento

Fluxo:

Dispositivo interno → Roteador → Internet

O roteador substitui o IP privado pelo IP público.

## Tipos de NAT

### Static NAT

Mapeia um IP privado para um IP público fixo.

### Dynamic NAT

Utiliza um conjunto de IPs públicos disponíveis.

### PAT (Port Address Translation)

Permite que vários dispositivos utilizem um único IP público.

Esse é o tipo mais comum em redes domésticas.

## Benefícios

- economia de endereços IPv4
- aumento de segurança
- ocultação da rede interna
