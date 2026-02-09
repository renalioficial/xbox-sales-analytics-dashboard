# 🎮 Dashboard de Vendas: Xbox Game Pass

> **Painel de controle para monitoramento de vendas de assinaturas e serviços adicionais.**

![Status](https://img.shields.io/badge/Status-Concluído-success) ![Excel](https://img.shields.io/badge/Excel-Dashboard-green)

## 📋 Sobre o Projeto
Este projeto apresenta um Dashboard de Vendas desenvolvido no Excel para acompanhar a performance comercial do **Xbox Game Pass**. 

O objetivo foi consolidar dados de assinantes em uma visão única, permitindo analisar o faturamento por tipo de plano e o impacto da venda de serviços extras (Add-ons).

### 🎯 O que o Dashboard Analisa?
Com base na base de dados transacional, o painel responde às seguintes perguntas:
1.  **Volume de Vendas:** Qual o valor total gerado pelas assinaturas?
2.  **Mix de Planos:** Quanto cada nível de assinatura (*Core, Standard, Ultimate*) representa no faturamento?
3.  **Serviços Adicionais:** Qual a receita gerada pela venda cruzada de *EA Play* e *Minecraft Season Pass*?
4.  **Perfil de Contrato:** Comparativo entre assinaturas Mensais, Trimestrais e Anuais.

---

## 🛠️ Estrutura Técnica
O projeto foi organizado para garantir a integridade dos dados e facilidade de atualização:

* **Base de Dados (`Bases`):** Tabela contendo o registro individual de cada venda, incluindo:
    * *Dados do Assinante:* ID, Nome.
    * *Detalhes do Plano:* Tipo (Core/Standard/Ultimate), Preço, Renovação Automática.
    * *Adicionais:* Flags e valores de EA Play e Minecraft.
    * *Financeiro:* Valor do Cupom e Valor Total da transação.

* **Cálculos (`Cálculos`):** Aba intermediária onde foram criadas as **Tabelas Dinâmicas** para agrupar os valores por categoria e alimentar os gráficos.

* **Front-end (`Dashboard`):** A interface final para o usuário, contendo:
    * **Segmentação de Dados (Slicers):** Filtros interativos por *Tipo de Assinatura* (Annual, Monthly, Quarterly).
    * **KPIs:** Cartões com os totais de vendas.
    * **Gráficos:** Visualização da distribuição de receita por plano.

---

## 🚀 Como Usar
1.  Baixe o arquivo `.xlsx`.
2.  Use os botões de filtro (Slicers) à esquerda para ver os dados de períodos ou tipos de contratos específicos.

---
