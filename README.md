# Laboratório I – Redes de Computadores  
Simulação de Rede com VLANs no Cisco Packet Tracer

## Sobre o projeto  

Este projeto consiste na modelagem e configuração de uma rede de computadores utilizando o Cisco Packet Tracer. A atividade foi desenvolvida na disciplina de Redes de Computadores (2025/1), com o objetivo de aplicar conceitos das camadas Física e de Enlace do modelo OSI.

A proposta envolve a criação de quatro redes distintas, cada uma representando uma casa, além de um nó central responsável pela interligação e organização das VLANs. O foco principal do trabalho é o isolamento lógico de redes por meio de VLANs, configuração de redes cabeadas e wireless, além da análise de quadros Ethernet e Wi-Fi no modo simulação.

---

## Objetivos  

- Aplicar conceitos das camadas Física e de Enlace do modelo OSI  
- Configurar VLANs para segmentação de rede  
- Trabalhar com redes Ethernet clássica e comutada  
- Configurar redes wireless com SSID distintos  
- Analisar cabeçalhos Ethernet e Wi-Fi  
- Verificar o funcionamento da comunicação utilizando o modo simulação  

---

## Funcionalidades Implementadas  

- Criação de quatro redes locais independentes  
- Configuração de VLANs para cada rede  
- Implementação de rede cabeada com hubs e switches  
- Implementação de rede comutada  
- Implementação de redes wireless com ponto de acesso  
- Configuração de servidores no switch central  
- Testes de conectividade com comando ping  
- Análise de PDUs no modo simulação  
- Verificação de isolamento entre VLANs  

---

## Estrutura da Rede  

### Rede 1  
- 6 PCs  
- 2 Hubs  
- 1 Switch  
- VLAN dedicada  

### Rede 2  
- 3 Laptops (Wireless)  
- 1 Access Point  
- 3 PCs (Cabeado)  
- 1 Switch  
- VLAN dedicada  

### Rede 3  
- 3 Laptops (Wireless)  
- 1 Access Point  
- VLAN dedicada  

### Rede 4  
- 3 PCs  
- 1 Switch  
- VLAN dedicada  

### Switch Central  
- 4 Servidores  
- 1 Switch central  
- Cada servidor associado a uma VLAN distinta  

---

## Tecnologias Utilizadas  

- Cisco Packet Tracer  
- VLAN (Virtual Local Area Network)  
- Ethernet  
- Wi-Fi (IEEE 802.11)  
- Modelo OSI  
- Protocolo ICMP  
- Endereçamento IPv4 (192.168.Y.X)  

---

## Conceitos Trabalhados  

- VLAN e segmentação lógica de rede  
- SSID  
- Cabeçalho Ethernet  
- Ethernet clássica e Ethernet comutada  
- Cabeçalho Wi-Fi  
- Camada MAC Wi-Fi  
- Quadros RTS/CTS  
- Encapsulamento e análise de PDUs  
- Comunicação intra-VLAN e isolamento inter-VLAN  

---

## Como executar o projeto  

### Pré-requisitos  

- Cisco Packet Tracer instalado (versão 8.x ou superior)

### Passos  

1. Abrir o Cisco Packet Tracer  
2. Carregar o arquivo `.pkt` disponível neste repositório  
3. Alternar para o modo Simulation  
4. Utilizar o Command Prompt dos dispositivos para executar pings  
5. Utilizar a ferramenta Simple PDU para testar comunicação  
6. Analisar as camadas do modelo OSI nas PDUs geradas  

---

## Testes Realizados  

- Ping entre dispositivos da mesma VLAN  
- Ping entre dispositivos conectados a hubs distintos  
- Ping entre dispositivos wireless e cabeados  
- Testes entre redes diferentes  
- Testes entre redes e seus respectivos servidores  

Os testes demonstram o funcionamento do isolamento por VLAN e o comportamento da comunicação no nível de enlace.

---

## Estrutura do Repositório  

- Arquivo Packet Tracer (.pkt)  
- Relatório técnico em PDF  
- README.md  

---
