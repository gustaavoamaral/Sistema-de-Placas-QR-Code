# 🟨 PlacaQR Pro

> SaaS para gerenciamento de QR Codes dinâmicos e plaquinhas físicas para empresas.


## 📌 Sobre o projeto

O **PlacaQR Pro** é uma plataforma SaaS desenvolvida para facilitar a criação, gerenciamento e monitoramento de QR Codes dinâmicos utilizados em plaquinhas físicas para estabelecimentos comerciais.

A solução permite criar lotes de plaquinhas, gerar QR Codes únicos, acompanhar ativações e monitorar os escaneamentos realizados pelos clientes.

O projeto foi desenvolvido pensando em empresas que vendem ou utilizam **plaquinhas de avaliação do Google**, permitindo transformar uma simples placa física em uma ferramenta mensurável de marketing.
<img width="1917" height="870" alt="image" src="https://github.com/user-attachments/assets/77ba64e2-686d-4148-be39-e40c1b7a0cf4" />

---

## 🚀 Funcionalidades

### QR Codes

- Criação de QR Codes únicos
- QR Codes dinâmicos
- Redirecionamento para diferentes destinos
- Ativação e desativação de códigos
- Identificação individual de cada placa
- Gerenciamento completo dos códigos
<img width="1910" height="868" alt="image" src="https://github.com/user-attachments/assets/f96cb21a-4e73-4d79-a6a2-ebdaa2209c2a" />

### 📦 Gestão de Lotes

- Criação de lotes de plaquinhas
- Geração em massa de QR Codes
- Controle de quantidade produzida
- Controle de códigos disponíveis
- Controle de códigos ativados
<img width="1901" height="866" alt="image" src="https://github.com/user-attachments/assets/15ac7b00-5556-4b17-9e93-11fd5e37e4a0" />

### 📊 Dashboard

O painel apresenta métricas em tempo real, incluindo:

- Total de QR Codes
- QR Codes disponíveis
- QR Codes ativados
- QR Codes desativados
- Total de scans
- Scans nas últimas 24 horas
- Volume de scans dos últimos 7 dias

### 📈 Analytics

O sistema permite acompanhar:

- Quantidade de escaneamentos
- Evolução dos scans
- Dispositivo utilizado
- Data e horário dos acessos
- Código da placa escaneada
- Destino do redirecionamento
<img width="1904" height="860" alt="image" src="https://github.com/user-attachments/assets/282f5d85-212e-473e-81b6-d29a866480da" />

### 📱 Detecção de dispositivos

Os acessos são classificados por:

- 📱 Mobile
- 💻 Desktop
- 📟 Tablet

---

## 🎨 Editor de Plaquinhas

A plataforma também possui uma área dedicada à criação e gerenciamento das artes utilizadas nas plaquinhas físicas.

A ideia é permitir que o usuário tenha todo o fluxo centralizado:

**Criação → QR Code → Arte → Impressão → Ativação → Monitoramento**

---

## 🧪 Simulador de Scans

O projeto possui um ambiente de testes que permite simular escaneamentos antes da distribuição das plaquinhas.

Isso facilita a validação do funcionamento dos QR Codes e dos redirecionamentos.

---

## 🔐 Segurança e Privacidade

O sistema foi desenvolvido considerando boas práticas de proteção de dados.

Os endereços IP utilizados para métricas são tratados com **hash SHA-256 unidirecional**, evitando o armazenamento direto do IP original.

O objetivo é coletar métricas úteis sem armazenar dados pessoais desnecessários dos usuários que escaneiam as placas.

---

## 🏗️ Arquitetura

O sistema é dividido em diferentes módulos:

```text
PlacaQR Pro
│
├── Dashboard
│   ├── Métricas
│   ├── Scans
│   └── Dispositivos
│
├── QR Codes
│   ├── Criação
│   ├── Ativação
│   └── Gerenciamento
│
├── Lotes
│   └── Geração de placas
│
├── Editor de Artes
│
├── Analytics
│
├── Simulador
│
└── Configurações
