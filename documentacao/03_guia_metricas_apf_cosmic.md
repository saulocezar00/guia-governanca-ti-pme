# 🏛️ Adaptação Prática: ITIL e COBIT para PMEs
# 📐 Guia de Métricas: APF e COSMIC

Métricas de software traduzem linhas de código em valor financeiro compreensível pela diretoria da empresa.

## 1. Análise de Pontos de Função (APF)
A APF mede o tamanho do software baseado nas funcionalidades entregues ao usuário (visão externa).

### Componentes de Análise:
* **ALI (Arquivos Lógicos Internos):** Dados mantidos dentro do sistema (ex: Banco de dados de Clientes).
* **AEE (Arquivos de Interface Externa):** Dados consultados de outros sistemas (ex: API de CEP).
* **EE (Entradas Externas):** Telas de cadastro, formulários.
* **CE (Consultas Externas):** Relatórios em tela, buscas.
* **SE (Saídas Externas):** Relatórios gerados para download, envio de e-mails fiscais.

## 2. Método COSMIC
Ideal para arquiteturas modernas (Microsserviços, APIs REST, IoT). Mede os movimentos de dados (*Data Movements*).

### Os 4 Movimentos do COSMIC:
1.  **Entry (E):** Dados entram do usuário/sistema externo para o software.
2.  **Exit (X):** Dados saem do software para o usuário/sistema externo.
3.  **Read (R):** O software lê dados do armazenamento persistente.
4.  **Write (W):** O software grava dados no armazenamento persistente.

> 💡 **Regra de Unidade:** Cada movimento equivale a 1 CFP (Cosmic Function Point).

## 📊 Aplicação do ROI (Retorno sobre Investimento)
Ao saber que um projeto tem 100 Pontos de Função e o custo da equipe foi de R$ 50.000,00, a empresa passa a saber seu custo por unidade de entrega:

$$Custo\ por\ PF = \frac{R\$\ 50.000,00}{100\ PF} = R\$\ 500,00\ por\ PF$$

Isso permite prever orçamentos futuros com precisão científica, eliminando o "achismo".
