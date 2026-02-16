# 💸 App de Organização de Finanças Pessoais com Vibe Coding da Poliana

Este projeto foi criado como resposta a um **desafio de projeto da DIO (Digital Innovation One)** usando como ferramentas o **Copilot Web** e o **Lovable**. O objetivo foi aplicar conceitos de **PRD (Product Requirements Document)** e **Vibe Coding** para desenvolver um aplicativo de finanças pessoais que utiliza linguagem natural para facilitar o controle financeiro.

PRD refinado no Copilot:

``` markdown

PRD – Aplicativo de Organização de Finanças Pessoais

Contexto
O aplicativo tem como objetivo simplificar o controle financeiro pessoal por meio de interações em linguagem natural.
Em vez de formulários complexos ou planilhas, o usuário conversa com o app como se fosse um “assistente financeiro”, tornando o processo mais acessível e intuitivo.

Problema
Muitos usuários abandonam aplicativos de finanças porque:
- Exigem entradas manuais extensas.
- Não oferecem personalização suficiente.
- Tornam o processo burocrático e pouco amigável.

O desafio é criar uma experiência fluida e personalizada, baseada em conversas, que incentive o usuário a manter o hábito de organizar suas finanças.

Público-Alvo
- Pessoas que desejam começar a organizar suas finanças de forma prática.
- Usuários iniciantes, sem experiência prévia em controle financeiro.
- Pessoas que buscam simplicidade e orientação amigável.

Funcionalidades-Chave
1. Registro de gastos via chat: o usuário descreve seus gastos em linguagem natural.
2. Classificação automática: o sistema identifica categorias (alimentação, transporte, lazer etc.).
3. Metas financeiras: definição e acompanhamento de objetivos (ex.: economizar R$ 500/mês).
4. Agente Financeiro: dicas personalizadas de economia e boas práticas.
5. Relatórios simples: visualizações claras e adaptadas ao perfil do usuário.

Diretriz de Design Universal
O aplicativo deve ser projetado com Design Universal, garantindo que o maior número possível de pessoas consiga utilizá-lo com boa experiência, independentemente de idade, nível de habilidade digital ou possíveis limitações físicas, cognitivas ou sensoriais.
Isso significa:
- Interface clara e acessível.
- Compatibilidade com leitores de tela.
- Uso de linguagem simples e inclusiva.
- Flexibilidade para diferentes estilos de interação (voz, texto, toques).

Entregável da IA
- Plano de MVP contendo:
  - Principais telas (chat, relatórios, metas).
  - Recursos essenciais (processamento de linguagem natural, categorização automática, geração de relatórios).
  - Estratégia de validação inicial (testes com grupo piloto de usuários iniciantes).
- Linguagem acessível e educativa, em português, para facilitar entendimento e engajamento.

```

Interações com o Lovable:

> Crie um app de finanças pessoais com base no seguinte PRD (Product Requirements Document): {PRD}

> Tentei criar uma meta chamada reserva de emergência, mas ela não apareceu no componente. A impressão que tive foi que apenas o Assistente Financeiro a reconheceu. Pode verificar por favor? Além disso, onde vejo os gráficos e extrato?

> Implemente a funcionalidade de criar metas pelo botão "Nova meta" (com formulário e estado local) {Quer que eu implemente a funcionalidade de criar metas pelo botão "Nova meta" (com formulário e estado local)? Ou prefere que isso seja persistido em banco de dados via Lovable Cloud?}

Resultado final no Lovable: https://personal-finance-talk.lovable.app

<img width="1919" height="1026" alt="image" src="https://github.com/user-attachments/assets/d20fdb6f-f29d-40f3-af57-e0694c5a4621" />


# Funcionalidades do Aplicativo de Finanças Pessoais

## 1. Dashboard Financeiro
- Exibe saldo atual, entradas e saídas.
- Mostra gastos por categoria (alimentação, transporte, lazer, moradia, saúde).
- Permite visão rápida da distribuição dos gastos.

## 2. Registro de Gastos via Chat
- Usuário registra despesas e receitas em linguagem natural.
- Sistema interpreta automaticamente o texto e transforma em transações.

## 3. Classificação Automática
- Transações categorizadas automaticamente (ex.: alimentação, transporte).
- Reduz esforço manual e aumenta precisão no controle.

## 4. Metas Financeiras
- Definição de objetivos (ex.: economizar um valor mensal).
- Aba dedicada a Metas para acompanhar progresso.

## 5. Relatórios Simples e Personalizados
- Relatórios claros e adaptados ao perfil do usuário.
- Aba Relatórios organiza informações de forma visual e acessível.

## 6. Agente Financeiro
- Assistente que dá dicas de economia e recomendações personalizadas.
- Interação por meio de conversas, tornando a experiência mais natural.

## 7. Design Universal
- Interface inclusiva e acessível para o maior número de pessoas.
- Compatibilidade com leitores de tela.
- Linguagem simples e inclusiva.
- Botões claros e flexibilidade de interação (voz, texto, toques).



## Reflexão:

### O que funcionou bem?

Os ajustes do PRD no Copilot foram imprescindíveis para a realização do app no Lovable, porque os créditos gratuitos diários são limitados e, com certeza, teriam acabado sem um bom resultado da aplicação no Lovable caso eu tivesse feito o refinamento por lá.

### O que não funcionou como o esperado?  

Quando o Lovable finalizou a criação da aplicação não apresentou uma página de login. O app já iniciou como se eu já tivesse feito o login na aplicação. Além disso, a página de metas tinha apenas um botão de Nova meta sem a funcionalidade criada e, por isso, foi necessário retornar ao prompt do Lovable para que ele corrigisse a aplicação. E, só para relatar, após essa correção os créditos gratuitos foram finalizados. 

### O que aprendeu sobre conversar com IAs?

Para que as IAs funcionem corretamente é necessário ser o mais clara e objetiva possível para atingir os resultados esperados. Talvez uma boa prática seja perguntar o que ela entendeu da minha soliticação, se tem alguma dúvida ou até talvez solicitar que me faça todas as perguntas necessárias antes da realização do projeto. No mais a interação com as IAs é muito simples e intuitiva. 


## 💬 Conclusão

"Vibe Coding é sobre clareza, curiosidade e criatividade, não sobre perfeição técnica. O verdadeiro objetivo aqui é aprender a pensar junto com a IA, transformando ideias em conceitos reais e enxergando a tecnologia como uma extensão do seu raciocínio criativo. Cada interação é um experimento, quanto mais clara for sua intenção, mais surpreendente será o resultado." (DIO)
