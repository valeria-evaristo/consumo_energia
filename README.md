# consumo_energia
Calculadora de consumo elétrico em python
# 🔌 Calculadora de Consumo de Energia (kWh)

![Status](https://img.shields.io/badge/status-concluído-brightgreen)
![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)
![GitHub](https://img.shields.io/badge/GitHub-repositório-black?logo=github)
![Energia](https://img.shields.io/badge/Energia-kWh-yellow?logo=power)

## 📌 Sobre o projeto

Este projeto é uma **calculadora de consumo elétrico inteligente**, desenvolvida em Python.  
O objetivo é ajudar usuários a estimar **quanto um aparelho consome de energia por mês**, usando dados simples como potência e horas de uso diário.

## 🧠 Como funciona

O programa pede:

- 📟 Nome do aparelho (ex.: Geladeira, Ventilador…)
- ⚡ Potência do aparelho em Watts (W)
- ⏱️ Tempo médio de uso diário em horas

Em seguida, calcula automaticamente o consumo mensal em **kWh/mês**.

---

## 🔢 Fórmula utilizada

\[
\text{kWh/mês} = \frac{\text{potência (W)} \times \text{horas/dia} \times 30}{1000}
\]

---

## ▶️ Como executar o programa

1. Certifique-se de ter o **Python 3** instalado.
2. Abra o terminal dentro da pasta do projeto.
3. Execute o comando:

```bash
python app.py
