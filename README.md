# Resumo - Quality Assurance (QA)  

## **1. Fundamentos de Garantia da Qualidade**  
### **Conceitos Básicos**  
- **QA x QC**: Garantia (processos) vs. Controle (execução).  
- **Cultura de qualidade**: Importância nas organizações.  

### **Tipos de Testes**  
| Tipo               | Objetivo                                                                 |  
|--------------------|--------------------------------------------------------------------------|  
| Unitário           | Testar componentes isolados (ex.: funções/métodos).                      |  
| Integração         | Verificar comunicação entre módulos.                                     |  
| Sistema            | Validar o software como um todo.                                         |  
| Aceitação          | Confirmar atendimento a requisitos do usuário (UAT).                     |  
| Regressão          | Garantir que novas alterações não quebrem funcionalidades existentes.    |  
| Exploratório       | Teste não scriptado, baseado em experiência e cenários reais.            |  

### **Planejamento e Ferramentas**  
- **Metodologias**: Cascata, Ágil (Scrum/Kanban), DevOps.  
- **Ferramentas**: Jira, TestRail, Zephyr (gestão de testes).  

---  

## **2. Planejamento e Estratégias de Teste**  
### **Critérios de Aceitação**  
- **User Stories** (Ágil) + **BDD** (Behavior-Driven Development):  
  - Exemplo: `Dado [contexto], Quando [ação], Então [resultado]`.  

### **Criação de Casos de Teste**  
- Estrutura clara: Pré-condições, passos, resultado esperado.  
- Priorização por **risco** e **impacto no negócio**.  

### **Métricas e Relatórios**  
- Exemplos:  
  - Taxa de defeitos (`Defeitos encontrados / Casos de teste executados`).  
  - Cobertura de testes (`% do código testado`).  

---  

## **3. Automação de Testes**  
### **Ferramentas Principais**  
- **Web**: Selenium, Cypress.  
- **Mobile**: Appium.  
- **APIs**: Postman, RestAssured.  
- **Performance**: JMeter (carga e estresse).  

### **Integração com CI/CD**  
- Exemplo de fluxo:
  Commit → Pipeline (GitHub Actions/Jenkins) → Testes Automáticos → Deploy

- **IA em QA**: Geração de casos de teste e análise de resultados (ex.: Testim, Applitools).  

---  

## **4. Controle e Monitoramento da Qualidade**  
### **Gestão de Bugs**  
- Fluxo: Identificação → Priorização → Correção → Validação.  
- Ferramentas: Jira, Bugzilla.  

### **Observabilidade (Observability)**  
- Pilares:  
- **Logs** (registros de eventos).  
- **Métricas** (dados quantitativos).  
- **Tracing** (rastreamento de transações).  
- Ferramentas: Prometheus, Grafana, ELK Stack.  

---  

## **Habilidades Desenvolvidas**  
✔ Implementar testes **manuais e automatizados**.  
✔ Criar **planos de teste** adaptáveis (Ágil/DevOps).  
✔ Integrar QA em **pipelines de CI/CD**.  
✔ Comunicar problemas e propor melhorias.  

