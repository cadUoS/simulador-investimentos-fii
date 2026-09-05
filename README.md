# 📊 SLV Invest — Simulador de Investimentos em Fundos Imobiliários

## 📌 Sobre o projeto

O **SLV Invest** é uma ferramenta desenvolvida em Microsoft Excel para auxiliar na simulação e no planejamento de investimentos em **Fundos de Investimento Imobiliário (FIIs)**.

A planilha foi desenvolvida com o objetivo de facilitar a visualização de diferentes cenários de investimento, permitindo ao usuário definir valores de aporte, período de investimento e taxa de rendimento, obtendo como resultado uma projeção do patrimônio acumulado e dos dividendos mensais.

O projeto foi desenvolvido como parte do desafio prático de Excel, aplicando conceitos de cálculos financeiros, organização de dados, automação de cálculos e visualização de informações.

---

## 🎯 Objetivos

- Criar uma ferramenta prática para simulação de investimentos;
- Aplicar conceitos de Excel e cálculos financeiros;
- Automatizar cálculos de patrimônio acumulado;
- Estimar dividendos mensais;
- Permitir a análise de diferentes períodos de investimento;
- Sugerir uma distribuição de investimentos de acordo com o perfil do investidor;
- Apresentar os resultados de forma clara e visual;
- Documentar o projeto utilizando o GitHub.

---

## 💰 Funcionalidades

A ferramenta possui diferentes recursos para auxiliar na simulação dos investimentos.

### ⚙️ Configurações

Permite informar:

- Salário mensal;
- Rendimento da carteira;
- Sugestão de investimento mensal.

### 📈 Investimento Mensal

Através dos parâmetros definidos pelo usuário, a planilha apresenta:

- Valor a investir por mês;
- Período de investimento;
- Taxa de rendimento mensal;
- Patrimônio acumulado;
- Estimativa de dividendo mensal.

### 📊 Cenários de investimento

A ferramenta apresenta projeções para diferentes períodos, permitindo comparar o crescimento do patrimônio e dos dividendos.

Os cenários disponíveis incluem:

- 2 anos;
- 5 anos;
- 8 anos;
- 10 anos;
- 12 anos.

### 👤 Perfil do investidor

A planilha também considera um perfil de investimento.

No exemplo apresentado neste projeto, foi utilizado o perfil:

**Moderado**

### 🏢 Distribuição dos FIIs

A ferramenta apresenta uma sugestão de distribuição do investimento mensal entre diferentes tipos de Fundos Imobiliários:

| Tipo de FII | Percentual sugerido | Valor |
|---|---:|---:|
| PAPEL | 32% | R$ 224,00 |
| TIJOLO | 35% | R$ 245,00 |
| HÍBRIDOS | 8% | R$ 56,00 |
| FOFs | 5% | R$ 35,00 |
| DESENVOLVIMENTO | 10% | R$ 70,00 |
| HOTELARIAS | 10% | R$ 70,00 |
| **Total** | **100%** | **R$ 700,00** |

---

## 🧮 Exemplo de simulação

Para demonstrar o funcionamento da ferramenta, foi realizada uma simulação utilizando os seguintes parâmetros:

| Parâmetro | Valor |
|---|---:|
| Salário | R$ 2.350,00 |
| Rendimento da carteira | 1% |
| Sugestão de investimento | R$ 705,00 |
| Investimento mensal | R$ 700,00 |
| Taxa de rendimento mensal | 1,08% |
| Perfil | Moderado |

### 📊 Resultado da simulação

Considerando um investimento mensal de **R$ 700,00**, a ferramenta apresenta diferentes projeções:

| Período | Patrimônio acumulado | Dividendo mensal |
|---|---:|---:|
| 2 anos | R$ 19.061,60 | R$ 114,37 |
| 5 anos | R$ 58.662,81 | R$ 351,98 |
| 8 anos | R$ 116.961,24 | R$ 701,77 |
| 10 anos | R$ 170.420,37 | R$ 1.022,52 |
| 12 anos | R$ 239.601,46 | R$ 1.437,61 |

Os valores apresentados são projeções calculadas com base nos parâmetros definidos na ferramenta.

---

## 📷 Demonstração

### Simulação — Perfil Moderado

Abaixo está um exemplo da ferramenta configurada com o perfil **Moderado**, investimento mensal de R$ 700,00 e taxa de rendimento mensal de 1,08%.

![Simulação SLV Invest](images/Simulação_Moderado.png)

---

## 🛠️ Tecnologias utilizadas

- **Microsoft Excel** — Desenvolvimento da ferramenta e realização dos cálculos;
- **GitHub** — Versionamento e compartilhamento do projeto;
- **Markdown** — Documentação do projeto.

---

## 📁 Estrutura do projeto

```text
simulador-investimentos-fii/
│
├── README.md
├── Simulador_Investimentos_FII.xlsx
│
└── images/
    └── Simulação_Moderado.png
    └── Simulação_Agressivo.png
    └── Simulação_Conservador.png
    └── Tabela_de_Apoio.png


⚠️ Aviso

Este projeto possui finalidade educacional e de simulação.

Os valores apresentados são projeções baseadas nos parâmetros informados na planilha e não representam garantia de rentabilidade futura ou recomendação de investimento.


👨‍💻 Autor

Eduardo Silva

Projeto desenvolvido como parte de um desafio prático de Excel, com foco em simulação de investimentos, cálculos financeiros e documentação técnica.
