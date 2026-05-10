# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 5/10/2026
Empresa: Abstergo Industries 
Responsável: Vitor Gustavo Da Silva Bernardes

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por [Seu Nome]. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

**Armazenamento Inteligente**
- Nome da ferramenta: Amazon S3 Intelligent-Tiering

- Foco da ferramenta: Otimização de custos de armazenamento de dados.

- Descrição de caso de uso: A Abstergo possui terabytes de arquivos antigos e backups que raramente são acessados, mas estão armazenados na camada mais cara. O S3 Intelligent-Tiering move automaticamente esses dados frios para camadas de armazenamento mais baratas (como o Glacier) sem impacto na performance ou necessidade de alterar o código da aplicação, gerando economia imediata.

**Dimensionamento de Servidores**
- Nome da ferramenta: AWS Compute Optimizer

- Foco da ferramenta: Rightsizing (dimensionamento correto) de recursos computacionais.

- Descrição de caso de uso: Utilizar inteligência artificial para analisar o consumo atual das instâncias EC2 da Abstergo. A ferramenta identificará servidores que estão superdimensionados (ex: pagando por 32GB de RAM quando usam apenas 4GB) e recomendará a redução para instâncias menores e mais baratas, cortando desperdícios imediatamente.

**AWS Budgets**
- Foco da ferramenta: Governança financeira e alertas de gastos.

- Descrição de caso de uso: Configurar orçamentos personalizados para impedir surpresas na fatura no final do mês. Caso o ambiente de desenvolvimento da Abstergo ultrapasse 80% do limite financeiro estipulado para a semana, o AWS Budgets enviará alertas automáticos para a equipe, permitindo desligar máquinas ociosas antes que o custo saia do controle.
## Conclusão
A implementação de ferramentas na empresa Abstergo Industries tem como esperado [descreva os benefícios gerais, ex: a redução drástica na fatura mensal e maior controle governamental dos recursos em nuvem], o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos

[Lista de anexos, como diagramas de arquitetura, planilhas de estimativa de custos (AWS Pricing Calculator), entre outros]

Assinatura do Responsável pelo Projeto:

Vitor Gustavo Da Silva Bernardes