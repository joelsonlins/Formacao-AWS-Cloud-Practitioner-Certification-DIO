
# RELATÓRIO DE IMPLEMENTAÇÃO DE MEDIDAS DE SEGURANÇA

**Data:** 05/12/2024  
**Empresa:** Abstergo Industries  
**Responsável:** Joelson Lins  

---

## Introdução

Este relatório apresenta o processo de implementação de ferramentas de segurança na empresa **Abstergo Industries**, realizado por **Joelson Lins**. O objetivo do projeto foi identificar e implementar três medidas de segurança utilizando os serviços da AWS, com a finalidade de fortalecer a proteção dos dados e recursos da empresa contra potenciais ameaças.

---

## Descrição do Projeto

O projeto foi estruturado com base em três medidas principais, descritas a seguir:

### **Medida 1: Ativação e Configuração do AWS Identity and Access Management (IAM)**

- **Descrição:** Criamos políticas de controle de acesso detalhadas para restringir privilégios aos colaboradores com base em suas funções específicas. Foram implementados princípios de **Least Privilege Access** e o uso obrigatório de autenticação multifator (MFA).  
- **Benefício:** Garantiu que apenas usuários autorizados possam acessar os recursos da AWS, reduzindo o risco de acessos não autorizados.  

---

### **Medida 2: Habilitação do AWS CloudTrail e Configuração de Logs Centralizados**

- **Descrição:** Implementamos o **AWS CloudTrail** para monitoramento detalhado das atividades realizadas nos recursos da AWS, com os logs armazenados de forma centralizada no Amazon S3 e protegidos por criptografia.  
- **Benefício:** Forneceu rastreabilidade completa das ações realizadas na conta da AWS, permitindo auditorias detalhadas e detecção de atividades suspeitas.  

---

### **Medida 3: Configuração do AWS Shield e WAF para Proteção contra Ataques DDoS**

- **Descrição:** Habilitamos o **AWS Shield Standard** e configuramos o **AWS WAF** para mitigar ameaças de negação de serviço (DDoS) e proteger as aplicações web contra ataques comuns, como injeção de SQL e scripts entre sites (XSS).  
- **Benefício:** Aumentou a resiliência das aplicações contra ataques externos, garantindo maior disponibilidade e proteção dos serviços web.  

---

## Conclusão

A implementação das ferramentas de segurança proporcionou à **Abstergo Industries** uma infraestrutura mais protegida e confiável. Essas medidas resultaram em:  

- Redução significativa dos riscos de acesso não autorizado;  
- Melhoria na rastreabilidade e auditoria de ações realizadas na infraestrutura;  
- Maior resiliência contra ataques externos e ameaças à disponibilidade.  

Recomenda-se a continuidade do uso das soluções implementadas, juntamente com treinamentos regulares para a equipe técnica, bem como a busca por atualizações contínuas nos serviços da AWS para acompanhar as melhores práticas de segurança.

---

## Anexos

1. **AWS Identity and Access Management (IAM)**
   - Documentação: [AWS IAM](https://docs.aws.amazon.com/pt_br/iam/)

2. **AWS CloudTrail**
   - Documentação: [AWS CloudTrail](https://docs.aws.amazon.com/pt_br/cloudtrail/)

3. **AWS Shield**
   - Documentação: [AWS Shield](https://docs.aws.amazon.com/pt_br/shield/)

4. **AWS WAF**
   - Documentação: [AWS CloudFront](https://docs.aws.amazon.com/pt_br/waf/)
 

---

**Assinatura do Responsável pelo Projeto:**  
Joelson Lins  