# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**Data:** 06/01/2026
**Empresa:** Abstergo Industries
**Responsável:** Sanderson Rhawan

---

## Introdução

Este relatório apresenta o processo de implementação de serviços em nuvem na empresa **Abstergo Industries**, realizado por **Sanderson Rhawan**, como parte do projeto final do módulo de **Computação em Nuvem** do curso **Santander 2025 – Ciência de Dados com Python (DIO)**.

O objetivo principal do projeto foi selecionar e implementar **3 serviços da AWS** com foco na **redução imediata de custos operacionais**, mantendo a eficiência, a escalabilidade e a segurança da infraestrutura de TI da empresa.

---

## Descrição do Projeto

O projeto de implementação foi dividido em **três etapas**, cada uma representando a adoção de um serviço AWS estratégico para otimização de custos.

---

### Etapa 1: Amazon EC2 Auto Scaling com Spot Instances

* **Nome da ferramenta:** Amazon EC2 Auto Scaling + EC2 Spot Instances
* **Foco da ferramenta:** Redução de custos com processamento computacional
* **Descrição de caso de uso:**
  A Abstergo Industries utiliza aplicações que apresentam variações significativas de carga ao longo do dia. Para otimizar custos, foi implementado o **Amazon EC2 Auto Scaling**, permitindo ajustar automaticamente a quantidade de instâncias conforme a demanda.

Além disso, foram utilizadas **EC2 Spot Instances** para workloads não críticos, como processamento de dados e tarefas em batch. As Spot Instances podem reduzir os custos de computação em até **90%** em comparação com instâncias sob demanda, gerando economia imediata sem impacto relevante nos serviços principais.

---

### Etapa 2: Amazon S3 com Intelligent-Tiering

* **Nome da ferramenta:** Amazon S3 Intelligent-Tiering
* **Foco da ferramenta:** Otimização de custos de armazenamento
* **Descrição de caso de uso:**
  A empresa mantém grande volume de dados históricos, logs e arquivos de apoio que não são acessados com frequência. Para reduzir custos de armazenamento, foi adotado o **Amazon S3 Intelligent-Tiering**, que move automaticamente os objetos entre camadas de acesso frequente e infrequente.

Essa estratégia elimina a necessidade de análises manuais sobre o padrão de acesso aos dados e garante economia contínua, pagando apenas pelo uso real do armazenamento.

---

### Etapa 3: AWS Cost Explorer e AWS Budgets

* **Nome da ferramenta:** AWS Cost Explorer + AWS Budgets
* **Foco da ferramenta:** Monitoramento e controle financeiro da nuvem
* **Descrição de caso de uso:**
  Para evitar gastos excessivos e identificar rapidamente oportunidades de economia, foram implementadas as ferramentas **AWS Cost Explorer** e **AWS Budgets**.

O Cost Explorer permite visualizar e analisar os custos detalhadamente por serviço, enquanto o AWS Budgets possibilita a criação de alertas automáticos quando os gastos se aproximam dos limites definidos. Essa etapa garante maior previsibilidade financeira e controle dos investimentos em nuvem.

---

## Conclusão

A implementação dos serviços AWS na empresa **Abstergo Industries** tem como resultado esperado a **redução imediata de custos operacionais**, maior controle financeiro, melhor aproveitamento dos recursos computacionais e escalabilidade automática da infraestrutura.

Com essas soluções, a empresa aumenta sua eficiência operacional e produtividade, ao mesmo tempo em que adota boas práticas de computação em nuvem. Recomenda-se a continuidade do uso das ferramentas implementadas e a avaliação constante de novos serviços AWS que possam trazer benefícios adicionais.

---

## Anexos

* Documentação oficial da AWS (EC2, S3, Cost Explorer e Budgets)
* Planilha de estimativa de custos antes e depois da implementação
* Diagramas de arquitetura da solução em nuvem

---

**Assinatura do Responsável pelo Projeto:**

Sanderson Rhawan


