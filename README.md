# 📚 AWS Certified Solutions Architect – Associate (SAA-C03)

> Repositório completo de estudos em Português do Brasil para quem quer passar no exame com entendimento real de arquitetura na AWS.

Portal publicado: https://thiago-code-lab.github.io/aws-solutions-architect-brasil/

## 🎯 Sobre este Repositório

Este material foi estruturado para um estudante de nível intermediário, que já usa AWS no dia a dia e já domina os fundamentos de cloud. O foco não é memorização cega: o objetivo é desenvolver o raciocínio esperado de um arquiteto de soluções, entendendo trade-offs entre resiliência, desempenho, segurança e custo.

O repositório foi pensado para funcionar bem no GitHub e no GitHub Pages. Cada módulo contém teoria, questões no estilo da prova, flashcards, cheatsheet, cenários arquiteturais, labs e curadoria de links oficiais. A ordem dos módulos acompanha os temas mais cobrados no exame e uma progressão de complexidade que faz sentido para revisão em 9 semanas.

## 📊 Estrutura e Domínios do Exame

| Domínio | Peso | O que cai na prática | Módulos principais |
|---|---:|---|---|
| Design Resilient Architectures | 30% | Alta disponibilidade, disaster recovery, desacoplamento, multi-AZ e multi-region | 05, 06, 08, 09, 13, 14, 21, 22, 24, 26 |
| Design High-Performing Architectures | 28% | Seleção de compute, caching, performance de storage, redes e bancos | 04, 06, 08, 10, 11, 12, 13, 16, 18 |
| Design Secure Applications and Architectures | 24% | IAM, KMS, isolamento de rede, criptografia, trilhas de auditoria e governança | 02, 03, 08, 09, 14, 17, 20, 23, 24, 25 |
| Design Cost-Optimized Architectures | 18% | Rightsizing, classes de storage, modelos de compra, serverless e automação | 04, 06, 15, 17, 21, 23 |

## 🗺️ Mapa de Estudos

### Semana 1
- Módulo 01: visão do exame, estratégia, pesos e serviços mais cobrados
- Módulo 02: IAM, KMS, Organizations, Identity Center e políticas
- Módulo 03: laboratório guiado de IAM e segurança

### Semana 2
- Módulo 04: EC2, EBS, placement groups e modelos de compra
- Módulo 05: ELB, ASG, health checks e escalabilidade

### Semana 3
- Módulo 06: S3, lifecycle, replicação, classes e segurança
- Módulo 07: laboratório avançado de S3
- Módulo 08: VPC, subnets, endpoints, rotas e segurança de rede
- Módulo 09: laboratório de VPC e redes

### Semana 4
- Módulo 10: bancos de dados para arquitetura (RDS, Aurora, DynamoDB, ElastiCache, Redshift)
- Módulo 11: laboratório de RDS e bancos relacionais
- Módulo 12: modelagem e padrões com DynamoDB
- Módulo 13: Route 53, CloudFront, OAC, WAF e Global Accelerator

### Semana 5
- Módulo 14: SQS, SNS, EventBridge e Step Functions
- Módulo 15: laboratório de mensageria SQS/SNS
- Módulo 16: ECS, EKS, Fargate, ECR e App Runner

### Semana 6
- Módulo 17: Lambda, API Gateway, authorizers e observabilidade serverless
- Módulo 18: Kinesis, Firehose, Glue, Athena, EMR e analytics

### Semana 7
- Módulo 19: serviços gerenciados de IA e ML mais cobrados
- Módulo 20: CloudWatch, CloudTrail, Config e X-Ray
- Módulo 21: DMS, MGN, DataSync, Snow Family e Transfer Family

### Semana 8
- Módulo 22: recuperação de desastres, continuidade, RTO/RPO e estratégias DR
- Módulo 23: AWS Organizations, governança multi-conta e otimização de custos
- Módulo 24: redes avançadas e conectividade híbrida (TGW, DX, VPN, PrivateLink)
- Módulo 25: criptografia com KMS e gestão de segredos com Secrets Manager/SSM

### Semana 9
- Módulo 26: Well-Architected Framework e DR patterns
- Módulo 27: estudos de caso reais
- Módulo 28: labs end-to-end
- Módulo 29: simulados completos
- Módulo 30 e 31: glossário e revisão de links oficiais

## 📁 Módulos

| # | Módulo | Domínio predominante | Status | Link |
|---|---|---|---|---|
| 01 | Introdução SAA-C03 | Foundation / Estratégia | ✅ Completo | [README](./01-Introducao-SAA-C03/README.md) |
| 02 | IAM e Segurança | Secure | ✅ Completo | [README](./02-IAM-e-Seguranca/README.md) |
| 03 | IAM e Segurança (Labs) | Secure (prática) | ✅ Completo | [Lab](./03-IAM-e-Seguranca-Labs/lab.md) |
| 04 | Computação EC2 | High-Performing | ✅ Completo | [README](./04-Computacao-EC2/README.md) |
| 05 | Alta Disponibilidade e Escalabilidade | Resilient | ✅ Completo | [README](./05-Alta-Disponibilidade-e-Escalabilidade/README.md) |
| 06 | Amazon S3 e Armazenamento | Resilient / Cost | ✅ Completo | [README](./06-Amazon-S3-e-Armazenamento/README.md) |
| 07 | S3 Avançado (Labs) | Resilient (prática) | ✅ Completo | [Lab](./07-S3-Avancado-Labs/lab.md) |
| 08 | VPC e Redes | Secure / Resilient | ✅ Completo | [README](./08-VPC-e-Redes/README.md) |
| 09 | VPC e Redes (Labs) | Secure (prática) | ✅ Completo | [Lab](./09-VPC-e-Redes-Labs/lab.md) |
| 10 | Banco de Dados | High-Performing | ✅ Completo | [README](./10-Banco-de-Dados/README.md) |
| 11 | RDS e Bancos Relacionais (Labs) | High-Performing (prática) | ✅ Completo | [Lab](./11-RDS-e-Bancos-Relacionais-Labs/lab.md) |
| 12 | DynamoDB (Labs) | High-Performing (prática) | ✅ Completo | [Lab](./12-DynamoDB/lab.md) |
| 13 | DNS, Route 53 e CloudFront | Resilient / Performance | ✅ Completo | [README](./13-DNS-Route53-e-CloudFront/README.md) |
| 14 | Desacoplamento: SQS, SNS, EventBridge | Resilient | ✅ Completo | [README](./14-Desacoplamento-SQS-SNS-EventBridge/README.md) |
| 15 | SQS e SNS (Labs) | Resilient (prática) | ✅ Completo | [Lab](./15-SQS-SNS-Mensageria-Labs/lab.md) |
| 16 | Containers: ECS, EKS, Fargate | High-Performing | ✅ Completo | [README](./16-Containers-ECS-EKS-Fargate/README.md) |
| 17 | Serverless: Lambda e API Gateway | Cost / Secure | ✅ Completo | [README](./17-Serverless-Lambda-API-Gateway/README.md) |
| 18 | Dados e Analytics | High-Performing | ✅ Completo | [README](./18-Dados-e-Analytics/README.md) |
| 19 | Machine Learning e IA | Serviços gerenciados | ✅ Completo | [README](./19-Machine-Learning-e-IA/README.md) |
| 20 | Monitoramento: CloudWatch e CloudTrail | Secure / Ops | ✅ Completo | [README](./20-Monitoramento-CloudWatch-CloudTrail/README.md) |
| 21 | Migração e Transferência | Resilient / Cost | ✅ Completo | [README](./21-Migracao-e-Transferencia/README.md) |
| 22 | Recuperação de Desastres e Continuidade | Resilient / Secure | ✅ Completo | [README](./22-Recuperacao-de-Desastres-e-Continuidade/README.md) |
| 23 | AWS Organizations, Governança e Custos | Secure / Cost | ✅ Completo | [README](./23-AWS-Organizations-Governanca-e-Custos/README.md) |
| 24 | Redes Avançadas e Conectividade Híbrida | Secure / Performance | ✅ Completo | [README](./24-Redes-Avancadas-e-Conectividade-Hibrida/README.md) |
| 25 | Criptografia, KMS e Gestão de Segredos | Secure | ✅ Completo | [README](./25-Criptografia-KMS-e-Gestao-de-Segredos/README.md) |
| 26 | Well-Architected Framework | Todos os domínios | ✅ Completo | [README](./26-Well-Architected-Framework/README.md) |
| 27 | Casos de Uso Reais | Todos os domínios | ✅ Completo | [README](./27-Casos-de-Uso-Reais/README.md) |
| 28 | Labs Práticos | Hands-on | ✅ Completo | [README](./28-Labs-Praticos/README.md) |
| 29 | Simulados e Questões | Todos os domínios | ✅ Completo | [README](./29-Simulados-e-Questoes/README.md) |
| 30 | Glossário | Revisão | ✅ Completo | [README](./30-Glossario/README.md) |
| 31 | Recursos e Links | Revisão | ✅ Completo | [README](./31-Recursos-e-Links/README.md) |

## 🚀 Como Usar Este Repositório

1. Comece pelo módulo 01 para alinhar expectativa, pesos e estratégia.
2. Estude os módulos 02 a 25 em ordem e use os módulos de laboratório para consolidar os temas críticos.
3. Ao final de cada módulo, resolva as questões antes de abrir o gabarito.
4. Use os flashcards para revisão espaçada e o cheatsheet para revisão rápida pré-simulado.
5. Rode os labs em us-east-1 sempre que possível para manter consistência com o material.
6. Feche a preparação com os estudos de caso, labs end-to-end e os três simulados completos.

## 🤝 Contribuições

Contribuições são bem-vindas, especialmente para:

- corrigir detalhes técnicos e limites de serviço
- melhorar cenários de questões e explicações de alternativas
- atualizar mudanças recentes dos serviços AWS
- adicionar diagramas ASCII mais claros e labs mais econômicos

Ao contribuir, prefira mudanças pequenas, tecnicamente justificadas e com links oficiais da AWS quando o assunto envolver comportamento específico de serviço.

## 📄 Licença

MIT
