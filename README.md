# ⚡ ChargeGrid Intelligence
> Sistema inteligente de gerenciamento de carregadores de veículos elétricos para condomínios e estacionamentos.
---
## 📋 Descrição da Solução
O **ChargeGrid Intelligence** é uma plataforma de gerenciamento inteligente de infraestrutura de carregamento para veículos elétricos (VEs). O sistema foi desenvolvido para resolver os principais problemas enfrentados por condomínios e estacionamentos que precisam oferecer carregamento a múltiplos veículos simultaneamente, sem sobrecarregar a rede elétrica e com um modelo de cobrança justo e automatizado.
A solução é estruturada em **4 pilares principais**:
| Pilar | Descrição |
|---|---|
| 🔋 Controle de Demanda | Gerenciamento inteligente da potência distribuída entre os carregadores |
| 💳 Tarifação e Pagamento | Cobrança automática e dinâmica por kWh consumido |
| 🔗 Interoperabilidade | Compatibilidade entre diferentes marcas e redes via protocolos abertos |
| 🤖 Inteligência Artificial | Otimização em tempo real da distribuição de carga |
---
## 🏗️ Arquitetura do Sistema
### Protocolos de Comunicação
| Protocolo | Camada | Função |
|---|---|---|
| **OCPP 2.0.1** | Carregador ↔ Servidor | Comunicação principal entre carregadores e sistema central |
| **ISO 15118** | Carro ↔ Carregador | Plug & Charge — autenticação e pagamento automático pelo cabo |
| **OCPI 2.2** | Rede ↔ Rede | Roaming entre diferentes redes de carregamento |
| **Modbus TCP** | Sistema ↔ Medidor | Leitura precisa do consumo elétrico por ponto |
### Lógica de Controle de Demanda (IA)
O sistema monitora o consumo total em tempo real. Quando a demanda ultrapassa 180 kW, a IA identifica o carregador com o veículo de maior bateria e reduz sua potência automaticamente, repetindo o processo até o consumo voltar ao limite seguro. Veículos com bateria abaixo de 20% têm prioridade e não são limitados.
---
## 🚀 Instruções de Uso
Acesse o protótipo funcional diretamente pelo navegador, sem instalar nada:
🔗 **https://felipemello987.github.io/Sprint2_alexandre/**  
O dashboard roda inteiramente no navegador e simula dados em tempo real, demonstrando os 4 pilares da solução.
---
## 🛠️ Materiais Técnicos
### Tecnologias do Protótipo
| Tecnologia | Uso |
|---|---|
| HTML5 | Estrutura da interface |
| CSS3 | Estilização e layout responsivo |
| JavaScript | Simulação de dados em tempo real |
| Chart.js | Gráfico de consumo de energia |
### Padrões e Normas de Referência
- **OCPP 2.0.1** — Open Charge Point Protocol (Open Charge Alliance)
- **ISO 15118** — Vehicle to Grid Communication Interface (ISO)
- **OCPI 2.2** — Open Charge Point Interface (EVRoaming Foundation)
- **ABNT NBR 16704** — Infraestrutura de recarga para veículos elétricos
- **Resolução ANEEL 1000/2021** — Tarifação de energia elétrica no Brasil
### Referências
- https://www.openchargealliance.org
- https://evroaming.org
- https://www.aneel.gov.br
- https://www.goodwe.com
---

*ChargeGrid Intelligence © 2026 — GoodWe Challenge*
