# network

Serviço de gerenciamento de rede para o Redstone OS.

## O que ele deve ser?
O `network` é o responsável por toda a pilha TCP/IP e conectividade em modo usuário. No Redstone, o kernel apenas move pacotes brutos; a lógica de protocolos reside aqui.

## O que precisa fazer?
- [ ] **Pilha de Protocolos**: Implementar TCP, UDP, IPv4/IPv6.
- [ ] **Gerenciamento de Interfaces**: Detectar e configurar placas de rede (Ethernet, Wi-Fi).
- [ ] **Configuração Dinâmica**: Cliente DHCP para obtenção automática de IP.
- [ ] **Resolução de Nomes**: Resolver domínios via DNS.
- [ ] **Roteamento**: Manter a tabela de rotas do sistema.
- [ ] **API IPC**: Oferecer sockets para outros aplicativos via IPC.
