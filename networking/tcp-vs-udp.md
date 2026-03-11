# Diferença entre TCP e UDP

TCP e UDP são protocolos da camada de transporte do modelo TCP/IP.

Eles são responsáveis por controlar como os dados são enviados entre dispositivos na rede.

## TCP (Transmission Control Protocol)

TCP é um protocolo orientado à conexão.

Isso significa que antes de enviar dados, uma conexão é estabelecida entre os dispositivos.

### Características

- confiável
- garante entrega dos dados
- verifica integridade dos pacotes
- controla ordem de entrega

### Processo de conexão

TCP utiliza o chamado **Three-Way Handshake**:

1. SYN
2. SYN-ACK
3. ACK

Esse processo estabelece a conexão entre cliente e servidor.

### Exemplos de uso

TCP é usado em aplicações que precisam de confiabilidade:

- HTTP / HTTPS
- FTP
- SSH
- Email

## UDP (User Datagram Protocol)

UDP é um protocolo sem conexão.

Ele envia pacotes diretamente sem verificar se foram entregues corretamente.

### Características

- mais rápido
- menor overhead
- não garante entrega
- não verifica ordem dos pacotes

### Exemplos de uso

UDP é utilizado quando velocidade é mais importante que confiabilidade.

Exemplos:

- streaming
- jogos online
- VoIP
- DNS

## Comparação

TCP

- confiável
- mais lento
- usado em aplicações críticas

UDP

- mais rápido
- menos confiável
- usado em aplicações em tempo real
