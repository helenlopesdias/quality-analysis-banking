# Análise de Qualidade e Riscos em Sistemas Financeiros

**Diagnóstico de dados sobre o impacto financeiro de falhas de software em transações críticas (PIX/TED).**

![Dashboard Preview](Dashboard_Quality_Risk.png)

## Sobre o Projeto
Este projeto simula um cenário real de uma instituição financeira (*FutureBank*) que enfrenta altos custos operacionais devido à detecção tardia de falhas em seu sistema de pagamentos.

O objetivo foi realizar uma **análise diagnóstica** utilizando dados históricos para calcular o **Custo da Má Qualidade (COPQ)** e justificar, através de dados, a migração de uma metodologia de desenvolvimento linear (Cascata) para um modelo de validação contínua (Modelo em V).

## Principais Descobertas (Insights)
A análise dos dados de incidentes do ano fiscal de 2023 revelou:
* **Custo Total de Falhas:** Identificado um desperdício de **R$ 949.600,00** em correções.
* **Gargalo de Processo:** **89,6%** desse custo é gerado por falhas descobertas apenas em ambiente de Produção.
* **Risco Crítico:** O módulo **PIX** é o maior ofensor em volume e severidade de falhas.
* **Sazonalidade:** Picos de instabilidade correlacionados a datas comerciais (Natal/Dia das Mães).

## 🛠️ Ferramentas e Técnicas Utilizadas
* **Análise de Dados:** Limpeza, saneamento e categorização de datasets.
* **Estatística Descritiva:** Cálculo de correlação e distribuição de frequências.
* **Business Intelligence:** Criação de Dashboard interativo e storytelling de dados.
* **Ferramenta:** Google Sheets (Tabelas Dinâmicas, Funções Condicionais, Visualização de Dados).

## Entregáveis do Projeto
* [ Acesse aqui o Scope of Work (SOW) Completo em PDF](Scope_of_Work_FutureBank.pdf)
* Análise de ROI e mitigação de riscos regulatórios.

---
*Nota: Este projeto utilizou dados sintéticos (fictícios) gerados para fins educacionais, respeitando as normas de privacidade e proteção de dados (LGPD).*
