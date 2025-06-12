# 📋 Product Backlog

Este é o backlog do produto, contendo as histórias de usuário priorizadas pelo Product Owner (PO).

> **Legenda:**
> - 🎯 *História de usuário*
> - 🛠️ *Tarefa técnica*
> - 📝 *Observações/comentários do PO ou equipe*
> - ✅ *Item concluído*

---

## 🧾 Lista de Itens do Backlog

| ID   | Tipo     | Prioridade | Descrição                                                                                                     | Pontos | Status     |
|------|----------|------------|---------------------------------------------------------------------------------------------------------------|--------|------------|
| US01 | 🎯 História de usuário | Alta       | Como usuário cuidador, quero criar uma conta para registrar dados dos supervisionados.                        | 3      | A fazer    |
| US02 | 🎯 História de usuário | Alta       | Como usuário guest, quero criar uma conta para apenas visualizar dados compartilhados.                       | 2      | A fazer    |
| US03 | 🎯 História de usuário | Alta       | Como qualquer usuário, quero fazer login e ver uma interface correspondente ao meu tipo de conta.            | 3      | A fazer    |
| US04 | 🎯 História de usuário | Alta       | Como cuidador, quero cadastrar múltiplos supervisionados para gerenciar individualmente cada um.             | 3      | A fazer    |
| US05 | 🎯 História de usuário | Alta       | Como cuidador, quero ver os dados de cada supervisionado organizadamente para facilitar o acompanhamento.    | 2      | A fazer    |
| US06 | 🎯 História de usuário | Média      | Como cuidador, quero indicar o nível de suporte (1 a 3) de cada supervisionado para melhor caracterização.   | 2      | A fazer    |
| US07 | 🎯 História de usuário | Alta       | Como cuidador, quero preencher o questionário BAMBI para cada supervisionado a fim de avaliar seletividade.  | 3      | A fazer    |
| US08 | 🎯 História de usuário | Alta       | Como sistema, desejo processar os dados do BAMBI e indicar o grau de seletividade alimentar.                  | 4      | A fazer    |
| US09 | 🎯 História de usuário | Alta       | Como cuidador, quero preencher o questionário de frequência alimentar para cada supervisionado.              | 3      | A fazer    |
| US10 | 🎯 História de usuário | Média      | Como cuidador, quero indicar os grupos sensoriais aceitos após o questionário de frequência alimentar.       | 2      | A fazer    |
| US11 | 🎯 História de usuário | Alta       | Como sistema, desejo criar o perfil alimentar a partir dos dados alimentares e sensoriais.                   | 4      | A fazer    |
| US12 | 🎯 História de usuário | Alta       | Como cuidador, quero receber o perfil alimentar de cada supervisionado em forma de relatório.                | 2      | A fazer    |
| US13 | 🎯 História de usuário | Alta       | Como sistema, desejo gerar um relatório de trocas alimentares com base no perfil e no grau de seletividade.  | 5      | A fazer    |
| US14 | 🎯 História de usuário | Alta       | Como cuidador, quero visualizar o relatório de trocas com sugestões agrupadas por categoria alimentar.       | 3      | A fazer    |
| TK01 | 🛠️ Tarefa técnica     | Alta       | Implementar autenticação com controle de tipo de usuário (guest/cuidador).                                  | 3      | A fazer    |
| TK02 | 🛠️ Tarefa técnica     | Alta       | Criar base de dados para armazenar supervisionados e seus dados associados.                                  | 4      | A fazer    |
| TK03 | 🛠️ Tarefa técnica     | Média      | Desenvolver componente de questionário BAMBI com processamento automático dos resultados.                    | 5      | A fazer    |
| TK04 | 🛠️ Tarefa técnica     | Média      | Implementar questionário de frequência alimentar com integração ao banco de dados.                           | 4      | A fazer    |
| TK05 | 🛠️ Tarefa técnica     | Alta       | Gerar PDF ou tela exportável com o relatório de trocas alimentares personalizado.                            | 4      | A fazer    |

---


## 🧱 Épicos do Produto

Abaixo estão os épicos que agrupam as funcionalidades do sistema em blocos de valor. Cada épico reúne histórias de usuário e tarefas técnicas relacionadas a um mesmo objetivo macro.

---

### 🧱 Épico 1: Gestão de Usuários

> Funcionalidades relacionadas ao cadastro, autenticação e diferenciação entre tipos de conta.

- **US01** 🎯 Como usuário cuidador, quero criar uma conta para registrar dados dos supervisionados.  
- **US02** 🎯 Como usuário guest, quero criar uma conta para apenas visualizar dados compartilhados.  
- **US03** 🎯 Como qualquer usuário, quero fazer login e ver uma interface correspondente ao meu tipo de conta.  
- **TK01** 🛠️ Implementar autenticação com controle de tipo de usuário (guest/cuidador).  

---

### 🧱 Épico 2: Cadastro e Gerenciamento de Supervisionados

> Funcionalidades para cadastrar, visualizar e organizar informações dos supervisionados.

- **US04** 🎯 Como cuidador, quero cadastrar múltiplos supervisionados para gerenciar individualmente cada um.  
- **US05** 🎯 Como cuidador, quero ver os dados de cada supervisionado organizadamente para facilitar o acompanhamento.  
- **US06** 🎯 Como cuidador, quero indicar o nível de suporte (1 a 3) de cada supervisionado para melhor caracterização.  
- **TK02** 🛠️ Criar base de dados para armazenar supervisionados e seus dados associados.  

---

### 🧱 Épico 3: Avaliação de Seletividade Alimentar

> Aplicação e processamento do questionário BAMBI para detectar seletividade alimentar.

- **US07** 🎯 Como cuidador, quero preencher o questionário BAMBI para cada supervisionado a fim de avaliar seletividade.  
- **US08** 🎯 Como sistema, desejo processar os dados do BAMBI e indicar o grau de seletividade alimentar.  
- **TK03** 🛠️ Desenvolver componente de questionário BAMBI com processamento automático dos resultados.  

---

### 🧱 Épico 4: Avaliação de Frequência Alimentar e Sensibilidade

> Registro de preferências alimentares e identificação de padrões sensoriais.

- **US09** 🎯 Como cuidador, quero preencher o questionário de frequência alimentar para cada supervisionado.  
- **US10** 🎯 Como cuidador, quero indicar os grupos sensoriais aceitos após o questionário de frequência alimentar.  
- **TK04** 🛠️ Implementar questionário de frequência alimentar com integração ao banco de dados.  

---

### 🧱 Épico 5: Geração de Perfil e Relatórios Personalizados

> Criação de perfis alimentares e sugestões de trocas com base nos dados coletados.

- **US11** 🎯 Como sistema, desejo criar o perfil alimentar a partir dos dados alimentares e sensoriais.  
- **US12** 🎯 Como cuidador, quero receber o perfil alimentar de cada supervisionado em forma de relatório.  
- **US13** 🎯 Como sistema, desejo gerar um relatório de trocas alimentares com base no perfil e no grau de seletividade.  
- **US14** 🎯 Como cuidador, quero visualizar o relatório de trocas com sugestões agrupadas por categoria alimentar.  
- **TK05** 🛠️ Gerar PDF ou tela exportável com o relatório de trocas alimentares personalizado.  

---



## 📌 Notas Adicionais

- 🔁 Backlog revisado em **12/06/2025**
- 🧪 Critérios de aceitação serão adicionados durante o refinamento de backlog.
- 💬 Comentários e dúvidas devem ser abertos como *Issues* no repositório.

