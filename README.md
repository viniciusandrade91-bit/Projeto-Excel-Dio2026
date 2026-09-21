# 📊 Simulador de Investimentos em Fundos Imobiliários (FIIs)

Ferramenta desenvolvida como parte do desafio prático da **DIO**, com o objetivo de automatizar cálculos financeiros e auxiliar investidores a planejarem sua liberdade financeira através de FIIs.

## 🚀 O que a ferramenta faz?
- Calcula o **patrimônio necessário** para atingir uma meta de renda passiva mensal (dividendos).
- Simula o **tempo (em anos)** necessário para alcançar o objetivo com base em aportes mensais e taxas de retorno.
- Calcula o **aporte mensal ideal** necessário para atingir a meta em um prazo fixo pré-determinado.
- Permite alternar entre diferentes perfis de investimento (Conservador, Moderado, Arrojado).

## 🧮 Principais Fórmulas Utilizadas
- Conversão de Taxa Anual para Mensal (Juros Compostos): `=(1 + TaxaAnual)^(1/12) - 1`
- Cálculo de Período/Tempo (`NPER`) para atingir a meta.
- Cálculo de Esforço de Aporte (`PGTO`).

## 📥 Como baixar e testar
1. Vá até a aba principal do repositório.
2. Baixe o arquivo `.xlsx` da planilha.
3. Abra no Microsoft Excel ou importe para o Google Sheets para testar as simulações!
