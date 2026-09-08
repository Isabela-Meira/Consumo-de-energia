# ⚡ Calculadora de Consumo Elétrico

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python\&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-Repositório-black?logo=github)
![Status](https://img.shields.io/badge/Status-Concluído-brightgreen)
![Energia](https://img.shields.io/badge/Energia-Consumo%20Elétrico-yellow)

## 📋 Sobre o projeto

Programa desenvolvido em **Python** para calcular o consumo mensal de energia elétrica de um aparelho e estimar seu custo.

O usuário informa o nome do aparelho, sua potência em watts e o tempo médio de uso diário.

## 🧮 Fórmula

```text
Consumo mensal = (Potência × Horas por dia × 30) ÷ 1000
```

O resultado é apresentado em **kWh/mês**.

### 💰 Custo estimado

O programa utiliza uma tarifa de referência de **R$ 0,75 por kWh**:

```text
Custo = Consumo mensal × 0,75
```

> A tarifa utilizada é apenas uma referência para fins didáticos.

## 🖥️ Exemplo

```text
Aparelho: Ferro elétrico
Potência: 2400 W
Uso diário: 1 hora
Consumo estimado: 72.00 kWh/mês
Custo estimado: R$ 54.00
```

## 🛠️ Tecnologias

* 🐍 Python
* 🌳 Git
* 🐙 GitHub

## ▶️ Como executar

1. Clone o repositório:

```bash
git clone https://github.com/Isabela-Meira/Consumo-de-energia.git
```

2. Entre na pasta:

```bash
cd Consumo-de-energia
```

3. Execute:

```bash
python app.py
```

No Windows, também pode usar:

```bash
py app.py
```

## 👩‍💻 Autora

**Isabela-Meira**

Projeto desenvolvido para fins acadêmicos em **Análise e Desenvolvimento de Sistemas (ADS)**.

---

⚡ **Consumo consciente começa com informação!**
