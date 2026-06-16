# CASE-IMPLANTACAO-DE-INFRAESTRUTURA-DE-TI

# Projeto de Infraestrutura de TI — Ótica Visão Clara
### São Carlos, SP — Março de 2025 [Fictício]

![Status](https://img.shields.io/badge/Status-Concluído-brightgreen)
![Documentação](https://img.shields.io/badge/Documentação-Completa-blue)
![Tipo](https://img.shields.io/badge/Tipo-Small%20Business-orange)
![Ano](https://img.shields.io/badge/Ano-2025-lightgrey)

> Repositório de documentação técnica referente ao projeto de implantação
> completa de infraestrutura de TI realizado pela equipe da **TechBase**
> para a Ótica Visão Clara, estabelecimento comercial localizado no centro de
> São Carlos/SP.

---

## 👥 Equipe do Projeto

| Membro | Função no Projeto |
|---|---|
| Rafael Mendonça | Analista de Infraestrutura Sênior — Líder Técnico |
| Hugo Vigatti | Suporte de Analista de Infraestrutura Junior — **Documentação Técnica e Aquisições** |
| Matheus Rangel | Técnico de Redes — Cabeamento e Certificação |
| Guilherme Luccione | Técnico de Suporte — Montagem e Instalação de SOs |

> 📌 **Minha responsabilidade neste projeto:** fiquei responsável pela
> elaboração de toda a documentação técnica (este repositório) e pelo
> processo de cotação, compra e recebimento de todos os equipamentos e
> insumos utilizados na implantação, via remoto, atuando como freelancer nesse projeto.

---

## 📋 Sobre o Projeto

A Ótica Visão Clara operava com uma infraestrutura de TI completamente
inadequada — computadores com mais de 10 anos de uso, rede sem segmentação,
ausência de backup e dados críticos em risco constante. Em janeiro de 2025,
um incidente de perda de dados motivou a contratação da TechBase para uma
reestruturação completa.

O projeto foi executado do zero, abrangendo desde a montagem física dos
computadores até a configuração de serviços de rede, firewall e rotinas
de manutenção, com entrega oficial em **28 de março de 2025**.

**Duração total:** ~4 semanas
**Equipe em campo:** 4 pessoas
**Investimento total:** R$ 53.489,30

---

## 📁 Estrutura do Repositório
infra-otica-visaoclara-2025/
│
├── 📄 README.md ← Você está aqui
│
├── 📂 docs/
│ ├── estudo-de-caso-completo.md ← Documentação técnica principal
│ ├── inventario-ativos.md ← Inventário de todos os equipamentos
│ ├── credenciais-referencia.md ← Estrutura de credenciais (sem senhas)
│ └── cronograma-execucao.md ← Timeline do projeto
│
├── 📂 rede/
│ ├── topologia-logica.md ← Diagrama lógico da rede
│ ├── topologia-fisica.md ← Diagrama físico / planta
│ ├── endereçamento-ip.md ← Tabela de IPs e sub-redes
│ └── vlans.md ← Configuração das VLANs
│
├── 📂 configuracoes/
│ ├── pfsense/
│ │ ├── regras-firewall.md ← Todas as regras configuradas
│ │ ├── dhcp-escopos.md ← Configuração dos escopos DHCP
│ │ └── vpn-openvpn.md ← Configuração da VPN
│ ├── servidor/
│ │ ├── ubuntu-server-setup.md ← Instalação e configuração base
│ │ ├── squid-proxy.md ← Configuração do proxy
│ │ ├── raid-backup.md ← RAID 1 e estratégia de backup
│ │ └── dns-bind9.md ← Configuração do DNS interno
│ └── switch/
│ └── tplink-sg2218-vlans.md ← Configuração do switch gerenciável
│
├── 📂 hardware/
│ ├── especificacoes-computadores.md ← Perfis A, B e C detalhados
│ ├── rack-organizacao.md ← Layout e organização do rack
│ └── cabeamento.md ← Metragens, certificação e padrões
│
├── 📂 financeiro/
│ ├── cotacoes.md ← Processo de cotação realizado
│ └── custos-detalhados.md ← Planilha de custos por categoria
│
├── 📂 manutencao/
│ ├── rotina-diaria.md ← Tarefas automáticas
│ ├── rotina-semanal.md ← Checklist semanal
│ ├── rotina-mensal.md ← Procedimentos mensais
│ └── plano-incidentes.md ← SLA e resposta a incidentes
│
└── 📂 treinamento/
├── manual-usuario.md ← Manual simplificado para usuários
└── guia-rapido.md ← Guia de problemas comuns

---

## Escopo da Implantação

### O que foi feito:

- [x] Montagem de **8 computadores** do zero (3 perfis distintos)
- [x] Instalação de **cabeamento Cat6** certificado (~273 metros)
- [x] Montagem e organização de **rack 12U**
- [x] Instalação e configuração do **pfSense** (firewall/roteador)
- [x] Configuração de **4 VLANs** com isolamento total
- [x] Serviço **DHCP** centralizado com reservas por MAC
- [x] Servidor **DNS** interno (Bind9)
- [x] **Proxy Squid** com controle de acesso e relatórios
- [x] **VPN OpenVPN** para acesso remoto seguro
- [x] **2 Access Points** gerenciados (Omada SDN Controller)
- [x] **Portal cativo** para Wi-Fi de clientes
- [x] **CFTV** com 4 câmeras IP e NVR
- [x] Estratégia de **backup 3-2-1** (local + HD externo + nuvem)
- [x] **RAID 1** no servidor para redundância de dados
- [x] **IDS/IPS** com Snort e pfBlockerNG
- [x] Instalação do **ERP** com migração de dados legados
- [x] **Treinamento** de todos os usuários
- [x] Documentação técnica completa

---

## Tecnologias e Ferramentas Utilizadas

**Sistemas Operacionais:**
![Ubuntu](https://img.shields.io/badge/Ubuntu_Server-22.04_LTS-E95420?logo=ubuntu)
![Windows](https://img.shields.io/badge/Windows_11-Pro-0078D4?logo=windows)
![pfSense](https://img.shields.io/badge/pfSense-CE_2.7.2-212121?logo=pfsense)

**Serviços de Rede:**
![Squid](https://img.shields.io/badge/Squid-Proxy-CF6C07)
![OpenVPN](https://img.shields.io/badge/OpenVPN-2.6-EA7E20?logo=openvpn)
![Bind9](https://img.shields.io/badge/BIND9-DNS-005A9C)
![Samba](https://img.shields.io/badge/Samba-File_Server-CC0000)

**Banco de Dados:**
![MariaDB](https://img.shields.io/badge/MariaDB-10.6-003545?logo=mariadb)

**Hardware de Rede:**
![TP-Link](https://img.shields.io/badge/TP--Link-Omada_EAP245-4DBEFF)
![TP-Link](https://img.shields.io/badge/TP--Link-TL--SG2218-4DBEFF)
![Furukawa](https://img.shields.io/badge/Furukawa-Cat6-green)

**Segurança:**
![Snort](https://img.shields.io/badge/Snort-IDS%2FIPS-CC0000)
![pfBlockerNG](https://img.shields.io/badge/pfBlockerNG-Blocklist-red)

---

## Resultados Alcançados

| Métrica | Antes | Depois |
|---|---|---|
| Tempo de boot das estações | 4–7 minutos | 18–25 segundos |
| Velocidade de rede interna | 10–100 Mbps | 1 Gbps |
| Backups funcionando | ❌ Nenhum | ✅ 3 cópias (3-2-1) |
| Segmentação de rede | ❌ Inexistente | ✅ 4 VLANs isoladas |
| Disponibilidade do ERP | ~85% | 99,6% |
| Acesso remoto da gestão | ❌ Impossível | ✅ VPN 24/7 |
| Monitoramento de internet | ❌ Inexistente | ✅ Squid + relatórios |

---

## Resumo Financeiro

| Categoria | Valor |
|---|---|
| Hardware — Computadores | R$ 21.327,30 |
| Hardware — Rede e Infraestrutura | R$ 10.349,00 |
| Software e Licenças | R$ 8.373,00 |
| Mão de Obra e Serviços | R$ 13.440,00 |
| **Total** | **R$ 53.489,30** |

> 💡 Para detalhamento completo das cotações e processo de compra,
> consulte [`/financeiro/cotacoes.md`](./financeiro/cotacoes.md)

---

## Processo de Aquisição

Uma das minhas principais responsabilidades neste projeto foi o
**processo completo de cotação e compra** dos equipamentos.

O processo seguiu as seguintes etapas:

1. **Levantamento da lista de materiais** com base no projeto técnico
   aprovado pelo líder técnico Rafael Mendonça
2. **Cotação em no mínimo 3 fornecedores** para cada item
   (KaBuM!, Pichau, Terabyte Shop, distribuidoras locais)
3. **Análise de custo-benefício** e verificação de prazo de entrega
4. **Emissão das ordens de compra** e acompanhamento dos pedidos
5. **Recebimento e conferência** dos itens contra a nota fiscal
6. **Registro no inventário** e entrega para a equipe técnica

O processo completo gerou uma economia de aproximadamente **R$ 2.800,00**
em relação ao primeiro orçamento fechado, por meio de negociação
com fornecedores e substituição de itens equivalentes com melhor
relação custo-benefício.

---

## Observações sobre este Repositório

- Nenhuma senha, chave privada ou dado sensível real está armazenado aqui
- Os endereços IP documentados são da rede interna (privada) do cliente
- O documento de credenciais foi entregue fisicamente ao cliente e
  **não faz parte** deste repositório
- Imagens e diagramas em Visio foram entregues diretamente ao cliente

---
