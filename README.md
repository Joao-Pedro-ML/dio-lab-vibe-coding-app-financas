# Prompt Final (PRD)

```txt
Prompt Otimizado para Geração do Plano de MVP
## Persona (Para a IA) Atue como um(a) Líder de Produto e Engenharia (Tech Lead) experiente, especializado em construir e validar MVPs (Produtos Mínimos Viáveis) de forma enxuta (lean).

## Contexto (O Briefing Original / PRD) Estou com a seguinte ideia de aplicativo, descrita neste PRD (Product Requirements Document):

Contexto: Quero criar um aplicativo de Organização de Finanças Pessoais que funcione por meio de conversas com o usuário. A ideia é facilitar o controle financeiro de forma simples e natural, sem formulários manuais ou planilhas complexas.

Problema: Muitas pessoas desistem de controlar seus gastos porque os apps atuais exigem muita entrada manual e pouca personalização. Quero resolver isso com uma experiência de conversa e recomendações automáticas de economia.

Público-Alvo: Pessoas que querem começar a organizar suas finanças de forma prática e sem complicação, principalmente iniciantes.

Funcionalidades-Chave (do Produto Final)

Registrar gastos via chat em linguagem natural.

Classificar automaticamente as transações.

Definir e acompanhar metas financeiras.

Receber dicas de economia do “Agente Financeiro”.

Visualizar relatórios simples e personalizados.

## A Tarefa (O Entregável Desejado) Com base no PRD acima, gere um Plano de MVP detalhado. O objetivo é focar exclusivamente em validar a hipótese central (a preferência pelo registro via chat) com o mínimo de recursos.

O plano deve ser prático, técnico e focado na ação.

## Critérios de Aceitação (O que o plano deve conter) Para ser completo, seu plano de MVP deve detalhar os 4 pilares a seguir:

Escopo do MVP e Hipótese Principal:

Defina qual é a hipótese principal que o MVP deve validar.

Defina o "ciclo de valor" mínimo (ex: Registrar -> Classificar -> Visualizar).

Telas e Fluxo de Usuário do MVP:

Descreva as telas essenciais (ou "momentos da conversa") necessárias para este MVP.

Inclua: Onboarding (Boas-vindas), a Tela de Chat (Principal), um Resumo/Dashboard simples e um fluxo mínimo de Metas.

Recursos e Pilares de Tecnologia Recomendados:

Liste as tecnologias necessárias, separadas por:

Frontend: (Ex: React Native, Flutter).

Backend: (Ex: Node.js, Python).

Processamento de Linguagem Natural (PLN): Detalhe as opções para o MVP (ex: de RegEx simples até serviços como Dialogflow ou Rasa) e explique como a classificação automática funcionaria inicialmente.

Plano de Validação Inicial (Crucial):

Descreva um plano de teste em duas etapas:

Etapa 1: Teste "Mágico de Oz" (Wizard of Oz): Explique como faríamos esse teste para validar a interface de chat sem construir a IA.

Etapa 2: Teste do MVP Funcional: Descreva como testar o MVP com um pequeno grupo de usuários (ex: 5-10 pessoas) e quais métricas de sucesso observar.
```

# Imagens

<img width="582" height="765" alt="image" src="https://github.com/user-attachments/assets/9f0c3480-64e7-4812-aa3e-f947dc0aac7e" />
<img width="1077" height="798" alt="image" src="https://github.com/user-attachments/assets/a2d43616-53af-431b-9096-eb05b119d716" />
<img width="1091" height="746" alt="image" src="https://github.com/user-attachments/assets/2663dc2e-7b91-4989-b781-ab0ed11441c5" />



# Resumo das funcionalidades
É um aplicativo de organização de finanças pessoais criado para iniciantes que acham os métodos tradicionais (planilhas, apps complexos) difíceis de usar.

O grande diferencial dele é a interface de conversa (chat). Em vez de preencher formulários, o usuário simplesmente "conversa" com um assistente virtual para:

1. Registrar gastos: (Ex: "Gastei R$ 50 no supermercado hoje.")

2. Classificar despesas: O app entende a frase e classifica o gasto automaticamente (ex: "Alimentação").

3. Definir metas: (Ex: "Quero gastar no máximo R$ 300 com iFood este mês.")

4. Visualizar relatórios: O usuário pode perguntar "Como estou esse mês?" e receber um resumo simples e gráficos de seus gastos.
