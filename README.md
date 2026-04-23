# 💸 App de Controle de Finanças Pessoais em uma só Conversa com Vibe Coding

## PRD Revisado e Modificado com auxilio do Copilot

```markdown
# PRD – App de Finanças Pessoais Conversacional

## Contexto
O aplicativo tem como objetivo simplificar o controle financeiro pessoal por meio de interações em linguagem natural.
A proposta é substituir formulários e planilhas complexas por uma experiência de conversa fluida, ágil e intuitiva, permitindo que o usuário registre e acompanhe suas finanças sem esforço.

## Problema
A maioria dos aplicativos de finanças exige entradas manuais extensas e oferece pouca personalização, o que leva muitos usuários a desistirem do controle financeiro.
Este app busca resolver esse problema com uma interface conversacional, recomendações automáticas e metas financeiras personalizadas.

## Público-Alvo
- Pessoas iniciantes no controle financeiro.
- Usuários que desejam praticidade e simplicidade sem lidar com planilhas ou sistemas complexos.
- Indivíduos que querem dicas rápidas e personalizadas para economizar.

## Funcionalidades-Chave
1. Registro de gastos via chat em linguagem natural.
2. Classificação automática das transações em categorias predefinidas.
3. Criação e acompanhamento de metas financeiras solicitadas pelo usuário.
4. Dicas diárias de economia fornecidas pelo “Agente Financeiro” com base nos hábitos e metas.
5. Relatórios personalizados e visuais simples, adaptados ao perfil do usuário.

## Categorias de Transações
- Casa
- Alimentação
- Lazer
- Viagem
- Saúde
- Educação
- Transporte
- Investimento
- Segurança

*(A lista deve ser dinâmica e atualizada conforme novas categorias forem informadas pelo usuário.)*

## MVP – Plano Inicial
### Telas Principais
1. Tela de Conversa
   - Chat com o “Agente Financeiro” para registrar gastos e receber dicas.
   - Entrada em linguagem natural.
2. Tela de Metas
   - Criação e acompanhamento de objetivos financeiros.
   - Exibição de progresso em barras ou gráficos simples.
3. Tela de Relatórios
   - Visualização de gastos por categoria.
   - Relatórios semanais/mensais em formato minimalista.
4. Tela de Configurações
   - Personalização de categorias.
   - Ajustes de notificações e preferências.

### Recursos Necessários
- Motor de NLP (Processamento de Linguagem Natural).
- Sistema de categorização automática.
- Banco de dados para registros e metas.
- Módulo de relatórios visuais.
- Notificações push para dicas diárias.

### Validação Inicial
- Testes com grupo piloto de usuários iniciantes.
- Coleta de feedback sobre clareza da conversa e utilidade das dicas.
- Ajustes rápidos de categorias e relatórios conforme uso real.

### Identidade Visual
- Paleta de cores: preto, cinza e branco.
- Estilo minimalista e sofisticado para reduzir estresse visual.
- Tipografia clara e legível.

## User Stories
1. Registro de Gastos
   - Como usuário iniciante, quero registrar meus gastos apenas digitando em linguagem natural, para não precisar preencher formulários complexos.
   - Exemplo: “Gastei R$ 50 com supermercado ontem”.

2. Criação de Metas
   - Como usuário que deseja economizar, quero criar metas financeiras de forma simples, para acompanhar meu progresso sem complicação.
   - Exemplo: “Quero guardar R$ 500 para viagem em 3 meses”.

3. Receber Dicas Diárias
   - Como usuário curioso, quero receber recomendações personalizadas de economia, para aprender hábitos financeiros melhores.
   - Exemplo: “Ontem você gastou mais em alimentação. Que tal planejar compras semanais para reduzir custos?”.

4. Relatórios Simples
   - Como usuário visual, quero ver relatórios claros e minimalistas, para entender rapidamente onde gasto mais.
   - Exemplo: “Alimentação: 40% dos seus gastos este mês”.

5. Personalização de Categorias
   - Como usuário com necessidades específicas, quero adicionar novas categorias de gastos, para que o app reflita minha realidade.
   - Exemplo: “Adicione categoria Pets”.

## User Flow
[Tela Inicial/Login]
        ↓
 [Tela de Conversa] ↔ [Tela de Metas]
        ↓
 [Tela de Relatórios]
        ↓
 [Tela de Configurações]
```
## Interações com o Lovable
> Crie um APP de finanças pessoais com base no seguinte PRD (Product Requirements Document): {PRD}

> Try to Fix: {Buid Error: src/integrations/lovable/index.ts(3,35): error TS2307: Cannot find module '@lovable.dev/cloud-auth-js' or its corresponding type declarations. }

> Os dados de entrada financeira estão sendo classificados nas categorias de gastos. Valores recebidos não são gastos e sim receita. As categorias são apenas para os gastos. Coloque todos os valores recebidos como receita.

> Adicionar um botão para excluir metas.{}

*Tela de correção de registro*
<img width="560" height="435" alt="Screenshot_2026-04-23_10-33-43" src="https://github.com/user-attachments/assets/57f62600-bcad-4739-b6fc-8abf17145ddd" />



Resultado final no Lovable: https://natural-money-flow.lovable.app

## Telas de Registro
Tela de Login e Registro de conta
<img width="1381" height="646" alt="Screenshot_2026-04-23_09-45-01" src="https://github.com/user-attachments/assets/ff6b0d75-0c53-49e6-87ba-a8eec272d6fd" />

Tela de confirmação de email
<img width="347" height="175" alt="Screenshot_2026-04-23_09-58-54" src="https://github.com/user-attachments/assets/b0b6e7a5-0288-4392-85a1-d37dd85ac395" />

Tela de Interface do usuário para registro de receitas/despesas
<img width="1144" height="873" alt="Screenshot_2026-04-23_10-13-00" src="https://github.com/user-attachments/assets/6eb91985-30d1-4fd9-8260-b089cc878038" />

Tela de Interface do usuário para metas
<img width="1119" height="641" alt="Screenshot_2026-04-23_11-09-37" src="https://github.com/user-attachments/assets/36bc8d8c-196d-4794-ab77-ee32f42bb01c" />

Tela de Interface do usuário para relatórios
<img width="1138" height="652" alt="Screenshot_2026-04-23_10-38-44" src="https://github.com/user-attachments/assets/6fd4b3b1-0a12-429a-a8c3-83b49bfd24ec" />

Tela de Interface do usuário para configurações
<img width="1117" height="619" alt="Screenshot_2026-04-23_10-38-57" src="https://github.com/user-attachments/assets/ef9c8135-363c-4c75-bdc2-5f99d280f017" />


## Resumo do que o *App de Controle Finanças Pessoais* faz
### 📱 App de Controle Finanças Pessoais Conversacional

#### 🌐 Central Financeira Conversacional
- Núcleo do app em formato de chat com o **Agente Financeiro**.
- Registro de gastos, criação de metas e adição de categorias usando linguagem natural.
- Exemplos:
  - “Gastei R$ 72 com Uber ontem”
  - “Quero guardar R$ 500 para viagem em 3 meses”
  - “Adicione categoria Pets”

#### 🔎 Classificação Automática de Transações
- Identificação automática de valor, categoria e data.
- Categorias pré-definidas: Casa, Alimentação, Transporte, Saúde, Educação, Lazer, Viagem, Investimento, Segurança.
- Possibilidade de adicionar novas categorias personalizadas.

#### 🎯 Metas Financeiras
- Criação de objetivos diretamente pelo chat.
- Progresso exibido em gráficos minimalistas.
- Exemplos:
  - “Meta de R$ 1.200 para reserva de emergência em 6 meses”
  - “Quero guardar R$ 500 para viagem em 3 meses”

#### 📊 Relatórios Simples e Minimalistas
- Visualização de gastos por categoria em gráficos (donut chart, barras).
- Resumo semanal e fluxo recente de despesas.
- Paleta de cores: preto, cinza e branco para transmitir sofisticação e reduzir estresse visual.

#### 💡 Dicas Diárias Personalizadas
- Recomendações automáticas baseadas nos hábitos do usuário.
- Exemplo:
  - “Ontem você gastou mais em alimentação. Que tal planejar compras semanais para reduzir custos?”

#### ⚙️ Configurações e Preferências
- Alternadores para ativar/desativar dicas diárias e resumo semanal.
- Personalização de categorias e notificações.
- Sincronização em nuvem (Cloud Sync ativo).

#### 📈 Indicadores Financeiros Rápidos
- **Saída do mês**: gastos acumulados.
- **Saldo mensal**: valor disponível.
- **Metas ativas**: número de objetivos em andamento.
- **Categorias**: quantidade de categorias registradas.

---

##### 🎨 Identidade Visual
- Estilo minimalista e sofisticado.
- Paleta em preto, cinza e branco.
- Tipografia clara e legível.
- Interface limpa, sem ruído visual, focada em clareza e agilidade.

## Reflexão sobre o processo
### O que funcionou bem?  
O refinamento do PRD realizado no Copilot, mesmo adicionando outras características, ajudou muito antes de interagir com o Lovable. Mesmo com o erro de registro de receitas ainda sobraram 0.7 créditos após 3 interações.
### O que não funcionou como o esperado?  
Esperava que a produção do app usasse menos créditos inicialmente. Ao final da primeira interação restaram apenas 1.4 créditos.

### O que aprendeu sobre conversar com IAs?
Aprendi que conversar com IA em linguagem natural é muito simples, mas a clareza do que se deseja é fundamental para obtenção de um resultado satisfatório.
