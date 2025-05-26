CAIO ALEXANDRE DOS SANTOS - FIAP

🔵 1. Rede Wireless com Segurança WPA2
Esta rede representa uma infraestrutura de uma pequena empresa ou ambiente doméstico utilizando um roteador Wi-Fi com segurança WPA2 ativada.

🔧 Componentes:
Roteador João: fornece conectividade sem fio e atribuição automática de IPs via DHCP.

Dispositivos conectados:
*Laptop João
*Laptop José
*Tablet
*Smartphone
*Impressora

🔐 Segurança:
Tipo: WPA2-Personal

Criptografia: AES

Chave pré-compartilhada: uma senha segura é exigida para que os dispositivos se conectem.

🧠 Funcionamento:
O roteador atua como servidor DHCP, atribuindo IPs automaticamente dentro da rede local (ex: 192.168.0.100 - 192.168.0.150).
Todos os dispositivos estão na mesma sub-rede, facilitando o compartilhamento de recursos como a impressora.

🟢 2. Rede Cabeada com Sub-redes /25
Esta rede representa um ambiente empresarial com duas sub-redes separadas para organizar dispositivos.

🧩 Divisão de sub-redes:
A rede principal 192.168.10.0/24 foi dividida em duas sub-redes /25, resultando em:

🔸 Sub-rede 1 (Laranja):
Faixa de IPs: 192.168.10.1 a 192.168.10.126
Máscara: 255.255.255.128 (/25)
Broadcast: 192.168.10.127

Dispositivos:
*PC0
*PC1
*PC2

🔹 Sub-rede 2 (Verde):
Faixa de IPs: 192.168.10.129 a 192.168.10.254
Máscara: 255.255.255.128 (/25)
Broadcast: 192.168.10.255

Dispositivos:
*PC3
*PC4
*PC5

🔧 Topologia:
Cada sub-rede está conectada a um switch.
Os switches se conectam a um roteador central, que faz o roteamento entre as sub-redes.
🌐 Objetivo da separação:
A divisão com sub-redes /25 permite maior organização, controle de tráfego, segurança e segmentação da rede para diferentes departamentos ou áreas da empresa.
