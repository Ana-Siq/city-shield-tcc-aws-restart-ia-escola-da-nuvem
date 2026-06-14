# city-shield-tcc-aws-restart-ia-escola-da-nuvem
Projeto desenvolvido a partir de um desafio inspirado no mercado real, exigindo análise e proposta de solução e apresentado como TCC (Trabalho de Conclusão de Curso) do curso AWS Re/Start + IA ministrada pela Escola da Nuvem

# 🛡️ CityShield

Sistema inteligente de segurança urbana com foco em monitoramento de eventos, análise em tempo real e integração de serviços AWS para apoio à gestão de cidades inteligentes. A solução combina segurança física e cibernética utilizando uma arquitetura orientada a eventos e serviços serverless da AWS. 

## 👥 Equipe Técnica (Grupo 6)

| Nome | Papel |
|------|--------|
| Gabriel Falcão da Cruz | Arquiteto |
| Fernanda Ferreira de Oliveira | Líder Técnica |
| Marcos Gomes de Lima | Desenvolvedor |
| Ana Paula da Silva Siqueira | Desenvolvedora |
| João Vitor Pontes | Desenvolvedor |

## 🚀 Objetivo

Fornecer uma plataforma escalável para:

- Monitoramento inteligente de ambientes urbanos;
- Processamento de eventos em tempo real;
- Detecção e resposta automática a ameaças;
- Armazenamento seguro de dados e evidências;
- Geração de alertas para equipes responsáveis. :contentReference[oaicite:1]{index=1}

## 🏗️ Arquitetura

A solução utiliza uma arquitetura cloud-native baseada em serviços AWS:

- AWS Lambda
- Amazon EventBridge
- Amazon DynamoDB
- Amazon S3
- Amazon Rekognition
- Amazon Kinesis
- Amazon SNS
- AWS GuardDuty
- AWS WAF
- AWS IAM

A aplicação foi projetada seguindo princípios de escalabilidade, segurança e baixo custo operacional. 

## 🛠️ Tecnologias

- AWS Cloud
- Serverless Architecture
- Event-Driven Architecture
- Segurança em Nuvem
- Inteligência Artificial
- Monitoramento e Observabilidade

### Serviços AWS (Serverless)

| Serviço | Categoria | Função |
|----------|----------|----------|
| Kinesis Video Streams | Ingestão de Dados | Streaming de vídeo de múltiplas câmeras |
| Rekognition | Inteligência Artificial (IA/ML) | Detecção e comparação facial |
| Lambda | Orquestração | Execução da lógica de negócio sem servidor, acionada por eventos |
| SNS | Notificações | Distribuição de alertas via SMS, push e webhooks |
| GuardDuty | Segurança | Detecção de ameaças cibernéticas utilizando Machine Learning |
| EventBridge | Gerenciamento de Eventos | Roteamento, integração e filtragem de eventos |
| WAF | Proteção de Aplicações | Bloqueio em tempo real de IPs maliciosos e ataques web |
| DynamoDB | Banco de Dados | Armazenamento de incidentes e registros em tempo real |
| S3 | Armazenamento | Armazenamento de evidências, imagens e logs para conformidade legal |

### Estimativa de Custo Mensal (Cenário Urbano Médio)

Baseado em uma cidade com **500 câmeras** em operação H24 + **infraestrutura digital moderada**:

| Serviço | Uso Estimado | Custo Mensal | Notas |
|---------|--------------|--------------|-------|
| **Kinesis Video Streams** | 500 câmeras × 1 Mbps | ~USD 3.500 | Maior custo; streaming contínuo |
| **Rekognition (Análise)** | ~200M frames/mês | ~USD 1.800 | Detecção facial ~0,01 USD por 1000 imagens |
| **Lambda (Orquestração)** | ~50M invocações/mês | ~USD 400 | Execução de funções dispara no evento |
| **SNS (Notificações)** | ~1M mensagens/mês | ~USD 50 | SMS + push notifications |
| **GuardDuty (Segurança)** | Análise contínua | ~USD 2.000 | Custo fixo por ativação; alto valor agregado |
| **EventBridge** | ~50M eventos/mês | ~USD 20 | Roteamento praticamente gratuito |
| **WAF (Proteção)** | ~100M requisições | ~USD 200 | Proteção em tempo real |
| **DynamoDB** | 10 GB/mês armazenado | ~USD 300 | Leitura/escrita sob demanda |
| **S3 (Evidências)** | ~500 GB/mês armazenado | ~USD 12 | Menos crítico; retenção longa |
| **Extras** (Transferência, logs) | - | ~USD 200 | Overhead de rede/CloudWatch |
| **TOTAL ESTIMADO** | - | **~USD 8.482/mês** | **~USD 101.784/ano** |


## 🎯 Principais Funcionalidades

* Monitoramento de eventos em tempo real;
* Reconhecimento e análise de imagens;
* Geração automática de alertas;
* Armazenamento de logs e evidências;
* Proteção contra ameaças cibernéticas;
* Controle de acesso baseado em permissões.

## 📚 Projeto Acadêmico

Este projeto foi desenvolvido como parte da formação da **Escola da Nuvem**, aplicando conceitos de computação em nuvem, segurança, automação e arquitetura serverless. 

CityShield © 2026 - Segurança Integrada Inteligente para Cidades Inteligentes
