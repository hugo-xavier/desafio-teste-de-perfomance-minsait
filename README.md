# 🧪 Desafio de Teste de Performance - Minsait

Este repositório contém a solução para o desafio de teste de performance utilizando o Apache JMeter.

---

## 📌 Objetivo

Simular e validar o comportamento de uma API de cadastro de usuários sob diferentes condições, utilizando JMeter para criação de cenários, execução de testes e análise de resultados.

---

## 🧰 Ferramentas utilizadas

- [Apache JMeter](httpsb para versionamento
- CSV para massa de dados

---

## 📁 Estrutura do repositório

- `Desafio - Testes de Performance com JMeter 2.jmx`: Plano de teste JMeter
- `massa de dados.csv`: Arquivo com dados de entrada para simulação
- `DesafioRepost_25_2.jtl`: Resultado da execução dos testes
- `README.md`: Documentação do desafio

---

## 🚀 Como executar

### Via interface gráfica (GUI)

1. Abra o JMeter
2. Importe o arquivo `.jmx`
3. Execute o plano de teste
4. Verifique os resultados no `View Results Tree` ou salve em `.jtl`

---

### Via terminal (modo não gráfico)

Para executar o teste e gerar o relatório HTML automaticamente:


jmeter.bat -n -t "Desafio - Testes de Performance com JMeter 2.jmx" -l "DesafioRepost_25_2.jtl" -e -o "relatorio"
