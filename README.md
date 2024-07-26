# Topologia de Rede

Este projeto visa configurar uma rede de computadores em topologia estrela utilizando o Cisco Packet Tracer.

## Cenário
Para o show da banda de Miguel, será necessário configurar uma rede de computadores. A comunicação entre os membros da equipe de produção, que estarão espalhados pelo teatro, é fundamental para manter todos informados e verificar se nada está fugindo do controle. O agente da banda decidiu modernizar a infraestrutura do show para melhorar essa comunicação. Para ajudá-los, você deve usar o Cisco Packet Tracer para criar uma topologia de rede estrela que permita a toda a equipe se comunicar facilmente.

Cada membro da equipe de produção possui um computador que precisa de uma conexão de rede para se comunicar com os outros membros.

## Sequência da Montagem da Topologia

1. **Cenário:**
   - Cada membro da equipe possui um computador que precisa de uma conexão de rede para se comunicar com os outros membros da produção.

2. **Montagem da Topologia:**
   - Foi feita uma nova topologia no Cisco Packet Tracer.
   - Um switch para no centro da área de trabalho.
   - Quatro PCs posicionados ao redor do switch, representando cada membro da equipe de produção.

3. **Conexão dos Dispositivos:**
   - Conectou-se cada PC a uma porta diferente no switch usando cabos ethernet.
   - A visualização é dos computadores da equipe de produção formando uma estrela ao redor do switch central.

4. **Configuração dos Endereços IP:**
   - Foi criado um senso de identidade para cada computador, atribuindo nomes e números de endereços IP.
   - Configurou-se os endereços IP para as interfaces dos PCs e do switch de acordo com a mesma sub-rede.
   - Endereçamento IP:
     - PC0: 192.168.1.1 / 255.255.255.0
     - PC1: 192.168.1.2 / 255.255.255.0
     - PC2: 192.168.1.3 / 255.255.255.0
     - PC3: 192.168.1.4 / 255.255.255.0

5. **Teste de Comunicação:**
   - Para verificar se todos os computadores estão devidamente configurados, acesse um dos PCs da equipe, abra o prompt de comando e tente fazer um ping para o endereço IP do computador de outro membro da equipe.
   - Exemplo de comando: `ping 192.168.1.3`

## Arquivos

- [Arquivo do Cisco Packet Tracer](./path/to/your/cisco-packet-tracer-file.pkt): Arquivo contendo a topologia configurada.
- [Print da Tela](./path/to/your/screenshot.png): Captura de tela da topologia e dos comandos ping executados para os outros três computadores.

## Instruções para Reproduzir

1. Baixe e instale o Cisco Packet Tracer.
2. Baixe o arquivo do Cisco Packet Tracer (.pkt) deste repositório.
3. Abra o Cisco Packet Tracer e carregue o arquivo baixado.
4. Verifique a configuração dos endereços IP em cada PC.
5. Teste a comunicação entre os PCs utilizando o comando ping.

## Contribuição

Sinta-se à vontade para contribuir com este projeto.

Se precisar de mais alguma coisa, estou à disposição!
