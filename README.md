# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**Data:** 15/07/2025  
**Empresa:** Abstergo Industries  
**Responsável:** Luciano dos Santos Bueno

---

## Introdução

Este relatório apresenta o processo de implementação de ferramentas na empresa **Abstergo Industries**, realizado por **Luciano dos Santos Bueno**. O objetivo do projeto foi selecionar e implementar três serviços da AWS com foco na **redução imediata de custos operacionais**, sem comprometer a escalabilidade e a segurança das operações.

---

## Descrição do Projeto

O projeto foi dividido em três etapas, cada uma abordando um serviço estratégico da AWS com potencial para otimização de custos:

### Etapa 1
- **Serviço:** Amazon S3 (Simple Storage Service)  
- **Foco:** Armazenamento escalável e econômico  
- **Descrição de caso de uso:**  
  Substituição de servidores de arquivos locais e serviços de armazenamento tradicionais por buckets S3.  
  Implementação de políticas de ciclo de vida (Lifecycle Policies) para arquivamento automático de dados antigos em classes como **S3 Glacier** e **S3 Intelligent-Tiering**, otimizando o custo conforme o uso real do armazenamento.

### Etapa 2
- **Serviço:** AWS Lambda  
- **Foco:** Execução de código sem provisionamento de servidores (serverless)  
- **Descrição de caso de uso:**  
  Migração de tarefas rotineiras e scripts agendados (como processamento de logs, notificações, e automações internas) para funções Lambda, eliminando a necessidade de manter instâncias EC2 sempre ativas. O modelo de cobrança por tempo de execução permitiu significativa economia nos custos de infraestrutura.

### Etapa 3
- **Serviço:** Amazon EC2 Spot Instances  
- **Foco:** Execução de workloads de forma econômica  
- **Descrição de caso de uso:**  
  Implementação de **instâncias spot** para workloads tolerantes a interrupções, como processamento de dados, testes automatizados e tarefas em lote. As instâncias spot proporcionaram economia de até **70% em comparação com instâncias sob demanda**, mantendo a performance esperada.

---

## Conclusão

A implementação dos serviços **Amazon S3, AWS Lambda e EC2 Spot Instances** na **Abstergo Industries** resultou em uma **redução significativa de custos operacionais**, além de oferecer maior escalabilidade, elasticidade e facilidade de gerenciamento da infraestrutura de TI.

Recomenda-se a continuidade da utilização desses serviços e a ampliação do uso de recursos AWS com foco em:

- Monitoramento via **CloudWatch**
- Otimização de custos com **AWS Cost Explorer**
- Adoção de práticas de **arquitetura serverless** sempre que aplicável

Essas ações garantirão uma operação mais eficiente, econômica e preparada para futuras demandas tecnológicas.

---

## Anexos

- Política de ciclo de vida do Amazon S3  
- Código das funções AWS Lambda  
- Logs de execução e custos estimados das Spot Instances  
- Relatório de comparação de custos antes/depois da migração

---

**Assinatura do Responsável pelo Projeto:**  
Luciano dos Santos Bueno
