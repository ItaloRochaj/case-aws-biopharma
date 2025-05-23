# 💡 Projeto: Implementação de Serviços AWS na Pharmavita Biotech

Este repositório contém o relatório de implementação de serviços em nuvem utilizando **Amazon Web Services (AWS)**, com foco em **redução de custos** e **otimização de processos** para a empresa fictícia **Pharmavita Biotech**.

## 🧪 Sobre a Empresa

**Pharmavita Biotech** é uma farmacêutica focada em pesquisa e desenvolvimento de medicamentos, que buscava modernizar sua infraestrutura de TI com soluções escaláveis, seguras e de baixo custo.

---

## 📌 Objetivo do Projeto

Elencar **3 serviços AWS estratégicos** com foco na **redução de custos imediata** e no aumento da eficiência dos processos internos.

---

## 🔧 Etapas do Projeto

### 📁 Etapa 1 – Amazon S3 (Intelligent-Tiering)
- **Foco:** Armazenamento inteligente de documentos regulatórios e dados de pesquisa.
- **Descrição:** Utilização do S3 Intelligent-Tiering para reduzir custos de armazenamento, com movimentação automática entre classes conforme o padrão de acesso aos dados.

---

### 🛢️ Etapa 2 – Amazon RDS (PostgreSQL)
- **Foco:** Banco de dados relacional gerenciado.
- **Descrição:** Substituição de banco local por RDS com alta disponibilidade, backups automatizados e failover entre zonas de disponibilidade.

---

### ⚙️ Etapa 3 – AWS Lambda + API Gateway
- **Foco:** Automatização de processos internos.
- **Descrição:** Utilização de funções serverless para geração de relatórios laboratoriais e envio de alertas, com custo sob demanda e sem necessidade de servidores dedicados.

---

## ✅ Benefícios Alcançados

- 📉 **Redução imediata de custos operacionais**
- ☁️ **Escalabilidade sob demanda**
- 🔒 **Alta disponibilidade e segurança**
- ⚡ **Automação de tarefas e ganho de produtividade**
- ![Arquitetura do case](https://github.com/ItaloRochaj/case-aws-biopharma/raw/main/imagens/Captura%20de%20tela%20de%202025-04-11%2012-29-30.png)


---

## 🛡️ Parte 2: Implementação de Medidas de Segurança

### 🔐 Medida 1 – AWS Identity and Access Management (IAM)
- **Descrição:** Definição de políticas de acesso com base em perfis específicos, ativação de autenticação multifatorial (MFA) e boas práticas de uso de contas. Garantia de que apenas usuários autorizados tenham acesso aos recursos da nuvem.

### 📋 Medida 2 – AWS CloudTrail
- **Descrição:** Ativação e configuração do AWS CloudTrail para auditoria e monitoramento de ações realizadas na conta AWS, com registros de todas as chamadas de API, acessos e alterações. Permite análise forense e maior transparência.

### 🛡️ Medida 3 – AWS WAF + AWS Shield
- **Descrição:** Proteção contra ataques de negação de serviço (DDoS) e filtragem de tráfego malicioso através do AWS Web Application Firewall e do AWS Shield, assegurando a integridade e a disponibilidade das aplicações.

---

## 🎯 Resultado Integrado
A união entre os serviços gerenciados da AWS e as camadas de segurança permitiu à Pharmavita Biotech alcançar uma infraestrutura moderna, segura e eficiente. Os ganhos incluem:

- 🔐 Conformidade com boas práticas e padrões de segurança da informação  
- 💸 Economia significativa com serviços sob demanda e gerenciamento automático  
- 🔄 Alta disponibilidade e tolerância a falhas  
- 📊 Visibilidade e controle de ações com auditoria detalhada  

---

## 🗺️ Arquitetura da Solução

![Diagrama da Arquitetura AWS com Medidas de Segurança Integradas](https://github.com/ItaloRochaj/case-aws-biopharma/blob/main/imagens/Untitled-2025-04-11-11235.png)


## 🧠 Recomendações Finais

- Continuar o uso das ferramentas implementadas
- Explorar novos serviços como Amazon CloudWatch, IAM, QuickSight e outras soluções de segurança e análise
- Monitorar constantemente os custos e métricas de uso via AWS Cost Explorer

---

### 👨🏻‍💻 Autor:
<table style="border=0">
  <tr>
    <td align="left">
      <a href="https://github.com/ItaloRochaj">
        <span><b>Italo Rocha</b></span>
      </a>
      <br>
      <span>Full-Stack Development</span>
    </td>
  </tr>
</table>

---

> Projeto fictício com fins educacionais, parte de estudos práticos sobre AWS e arquitetura em nuvem.
