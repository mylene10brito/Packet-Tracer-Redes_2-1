 Topologia de Interconexão com Servidor CentralizadoDescrição Visual: A rede possui um roteador central conectado a dois switches. O switch da esquerda atende a dois PCs (PC0 e PC1), enquanto o switch da direita atende a mais dois PCs (PC2 e PC3). O diferencial desta topologia é um servidor central (Server0) conectado diretamente a ambos os switches (ou atuando como ponte), criando um ponto compartilhado na parte inferior.Foco do Laboratório: Comunicação inter-redes e testes de acesso a serviços centralizados.
 
<img width="1999" height="820" alt="lab1" src="https://github.com/user-attachments/assets/3ce29414-804b-410d-9b36-ef4e2ac66257" />

Infraestrutura Corporativa Básica com Redes Sem Fio (WLAN)Descrição Visual: Uma topologia mais robusta dividida em duas grandes sub-redes conectadas por um roteador central ISR4331. A rede da esquerda utiliza o bloco 172.16.10.0/24 e a da direita utiliza o bloco 192.168.0.0/23. Cada lado possui um switch, um servidor dedicado no topo e um roteador sem fio doméstico (WRT300N) na parte inferior, distribuindo sinal Wi-Fi para três laptops de cada lado.Foco do Laboratório: Integração de redes cabeadas e sem fio (WLAN), além de configuração de serviços de rede (como DHCP e DNS nos servidores).

<img width="1999" height="820" alt="lab2" src="https://github.com/user-attachments/assets/30f6344a-5a25-42f2-b939-80bd7cd7fb34" />

Segmentação de Redes com Sub-redes de Tamanho Fixo (Subnetting)Descrição Visual: Similar à estrutura anterior, mas focada estritamente em divisão de sub-redes. A rede da esquerda foi calculada para o bloco 192.168.1.0/28 (máscara 255.255.255.240, permitindo até 14 hosts), alimentando dois PCs, um servidor e três laptops via Wi-Fi. A rede da direita utiliza o bloco 192.168.0.0/27 (máscara 255.255.255.224, permitindo até 30 hosts), alimentando dois PCs, um servidor e três laptops.Foco do Laboratório: Aplicação prática de cálculo de sub-redes (Subnetting/FLSM) e otimização do espaço de endereçamento IP.

<img width="1999" height="820" alt="lab3" src="https://github.com/user-attachments/assets/30e03030-858d-4be0-af3f-865e08251802" />

 Estrutura Clássica de Roteamento entre Duas LANsDescrição Visual: É o modelo fundamental de roteamento. Um roteador central interconecta duas LANs geograficamente ou logicamente separadas. A LAN da esquerda possui um servidor, um switch e dois PCs (PC0 e PC1). A LAN da direita replica exatamente a mesma estrutura, com um servidor, um switch e dois PCs (PC2 e PC3). Todas as conexões estão verdes e ativas.Foco do Laboratório: Fundamentos de roteamento unicast e isolamento de domínios de broadcast.

 <img width="1999" height="820" alt="lab4" src="https://github.com/user-attachments/assets/a6753c45-a6ae-46ca-99fb-794350496b25" />

 Rede de Alta Densidade e Escalabilidade (VLSM)Descrição Visual: A topologia mais complexa e povoada do conjunto. Apresenta um roteador no topo gerenciando duas redes de alta densidade de dispositivos. A rede da esquerda (192.168.1.0/28) possui dois servidores, três PCs cabeados e três laptops sem fio. A rede da direita (192.168.0.0/27) possui um servidor, três PCs cabeados e quatro laptops conectados ao roteador wireless.Foco do Laboratório: Validação de desempenho, dimensionamento de redes com VLSM de alta densidade e gerenciamento de escopo DHCP.

 <img width="1999" height="820" alt="lab5" src="https://github.com/user-attachments/assets/3f4f2573-9732-46a4-838d-22178e2748fa" />
