# 02 - Test Plan  
## E-commerce - SauceDemo

---

## 1. Introdução

Este documento descreve o plano de testes para o e-commerce SauceDemo.  
O objetivo é validar os principais fluxos críticos da aplicação, desde a autenticação do usuário até a finalização da compra, garantindo que o sistema esteja funcional, estável e alinhado às regras de negócio esperadas.

---

## 2. Objetivo do Plano de Testes

Garantir que as funcionalidades críticas do sistema estejam operando corretamente, reduzindo o risco de falhas em produção e assegurando conformidade com os critérios de aceite definidos.

Os testes serão estruturados para cobrir integralmente os fluxos principais do sistema:

- Login  
- Listagem de Produtos (Product Listing)  
- Carrinho de Compras (Cart)  
- Processo de Checkout  

---

## 3. Escopo

### 3.1 Dentro do Escopo

- Login  
- Listagem de Produtos  
- Carrinho de Compras  
- Processo de Checkout  

### 3.2 Fora do Escopo

- Página Home institucional  
- About Us  
- Blog  

---

## 4. Ambiente de Testes

- **URL da aplicação:** https://sauce-demo.myshopify.com/  
- **Sistema Operacional:** Windows 11  
- **Navegador:** Google Chrome (versão estável mais recente)  
- **Dispositivo:** Desktop  
- **Ferramentas de apoio:**  
  - DevTools (Chrome)  
  - Cypress (para futura automação)

---

## 5. Estratégia de Execução

A execução dos testes seguirá a seguinte ordem:

1. Análise dos requisitos e critérios de aceite  
2. Criação dos cenários de teste  
3. Elaboração dos casos de teste  
4. Execução de testes manuais  
5. Registro e reporte de bugs  
6. Reteste após correções  
7. Execução de testes de regressão  
8. Automação dos fluxos críticos (quando aplicável)  

Serão aplicadas as seguintes abordagens:

- Testes Funcionais  
- Testes Exploratórios  
- Testes de Interface (UI)  
- Testes de Regressão  

---

## 6. Critérios de Entrada

Os testes poderão ser iniciados quando:

- A funcionalidade estiver desenvolvida e disponível para validação  
- Os critérios de aceite estiverem definidos  
- As regras de negócio estiverem claras  
- O ambiente estiver acessível e estável  

---

## 7. Critérios de Saída

Os testes serão considerados concluídos quando:

- Todos os cenários planejados forem executados  
- Bugs críticos e de alta severidade estiverem corrigidos ou formalmente aceitos pelo time  
- Os fluxos principais estiverem validados  
- Evidências da execução estiverem documentadas  

---

## 8. Cronograma (Simulado)

- Dia 1 – Análise de requisitos  
- Dia 2 – Criação de cenários e casos de teste  
- Dia 3 – Execução dos testes manuais  
- Dia 4 – Retestes e regressão  

---

## 9. Riscos e Mitigações

| Risco | Mitigação |
|-------|------------|
| Requisitos não documentados | Realizar análise exploratória e registrar dúvidas |
| Instabilidade do ambiente | Validar ambiente antes da execução |
| Falta de massa de teste | Criar dados de teste controlados |
| Mudanças inesperadas na aplicação | Reexecutar cenários críticos |

---

## 10. Entregáveis

- Documento de Estratégia de Testes  
- Documento de Plano de Testes  
- Documento de Cenários de Teste  
- Casos de Teste detalhados  
- Relatório de Bugs  
- Evidências (prints e registros)  
- Scripts de automação (quando aplicável)  

---