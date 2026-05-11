# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**Data:** 10/05/2026
**Empresa:** Abstergo Industries
**Responsável:** Vitor Gustavo da Silva Bernardes

## Introdução

Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Vitor Gustavo da Silva Bernardes. O objetivo do projeto foi elencar 3 serviços AWS com a finalidade de realizar a diminuição de custos operacionais imediatos e otimizar o uso da infraestrutura em nuvem.

## Descrição do Projeto

O projeto foi estruturado para atacar as três principais frentes de desperdício: armazenamento ineficiente, recursos superdimensionados e falta de visibilidade financeira.

**Etapa 1: Armazenamento Inteligente**

* **Nome da ferramenta:** Amazon S3 Intelligent-Tiering
* **Foco da ferramenta:** Otimização automática de custos de armazenamento.
* **Descrição de caso de uso:** A Abstergo possui terabytes de arquivos e backups raramente acessados em camadas caras. O S3 Intelligent-Tiering move esses dados automaticamente para camadas de baixo custo (como Glacier) sem impacto na performance ou necessidade de alteração no código, gerando economia imediata.

**Etapa 2: Dimensionamento de Servidores**

* **Nome da ferramenta:** AWS Compute Optimizer
* **Foco da ferramenta:** *Rightsizing* (ajuste de escala) de recursos computacionais.
* **Descrição de caso de uso:** Utiliza IA para analisar o consumo real das instâncias EC2. A ferramenta identifica servidores superdimensionados (ex: pagando por 32GB de RAM quando usam apenas 4GB) e recomenda instâncias menores e mais baratas, eliminando o pagamento por recursos ociosos.

**Etapa 3: Governança e Controle**

* **Nome da ferramenta:** AWS Budgets
* **Foco da ferramenta:** Gestão financeira e alertas de gastos em tempo real.
* **Descrição de caso de uso:** Implementação de orçamentos personalizados com alertas automáticos. Caso os custos de desenvolvimento ultrapassem 80% do limite mensal, a equipe é notificada imediatamente para agir, evitando surpresas na fatura e garantindo previsibilidade orçamentária.

## Conclusão

A implementação das ferramentas S3 Intelligent-Tiering, AWS Compute Optimizer e AWS Budgets na Abstergo Industries deve resultar em uma redução drástica na fatura mensal e um controle governamental superior dos recursos. Essas medidas aumentam a eficiência operacional e permitem que a empresa reinvista o capital economizado em inovação. Recomenda-se a revisão periódica dessas métricas para manter a infraestrutura sempre otimizada.

---

**Assinatura:**
Vitor Gustavo da Silva Bernardes

---