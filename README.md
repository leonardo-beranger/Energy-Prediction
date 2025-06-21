# Dataset – Consumo Energético de Supermercado em Curitiba (2024–2025)

## 📌 Objetivo

Este dataset simula o consumo energético horário de uma unidade comercial do setor varejista — um supermercado localizado em Curitiba, Paraná, Brasil — no período de **1º de janeiro de 2024 até o dia anterior à data atual (junho de 2025)**.

Ele foi criado com o propósito de servir como base para:
- Modelagem preditiva de consumo energético
- Estudos de eficiência energética
- Monitoramento de carga horária
- Análise de impacto climático (interno e externo) no consumo

## 🏢 Perfil da Empresa

- **Setor:** Varejo alimentício (supermercado)
- **Localização:** Curitiba, PR – Brasil
- **Tipo de operação:** Funcionamento contínuo (24/7 ou com carga estendida)

## 🔧 Variáveis Contidas

| Variável                     | Tipo      | Descrição                                                                 |
|-----------------------------|-----------|---------------------------------------------------------------------------|
| `datetime`                  | Data/Hora | Data e hora de cada registro (intervalo horário)                         |
| `consumo_RTU_kWh`           | Numérica  | Consumo horário em kWh do sistema de climatização tipo RTU              |
| `consumo_Frio_Alimentar_kWh`| Numérica  | Consumo horário em kWh de equipamentos de refrigeração de alimentos      |
| `consumo_Iluminacao_kWh`    | Numérica  | Consumo horário em kWh do sistema de iluminação                          |
| `consumo_Outros_kWh`        | Numérica  | Consumo horário de outros equipamentos diversos                          |
| `consumo_total_kWh`         | Numérica  | Soma total do consumo horário (kWh) de todos os equipamentos             |
| `demanda_kW`                | Numérica  | Demanda elétrica registrada no horário (pico de potência) em kW          |
| `temperatura_interna_C`     | Numérica  | Temperatura interna simulada da loja (em ºC)                             |
| `temperatura_externa_C`     | Numérica  | Temperatura externa em Curitiba no horário (em ºC)                       |

## ⚙️ Equipamentos Considerados

- **RTU (Rooftop Unit)** – sistema de ar-condicionado comercial
- **Frio Alimentar** – balcões refrigerados, câmaras frias, freezers
- **Iluminação** – refletores, luminárias LED e fluorescentes
- **Outros** – caixas, balanças, computadores, expositores, etc.

## 📈 Possibilidades de Análise

- Previsão de consumo e demanda com modelos de Machine Learning
- Estudos de correlação entre temperatura externa e consumo energético
- Geração de curvas de carga horária e sazonalidade
- Simulação de impacto de projetos de eficiência energética
