# Prompts de IA do meu POS

Todos os prompts foram usados com o Claude. Substitua o que está entre colchetes.
Cuidado: não cole dados sensíveis da empresa ou de terceiros.

## 1. Triagem da caixa de entrada

```
Você é meu assistente de organização. Abaixo estão anotações soltas da minha semana.
Transforme cada item em uma tarefa e devolva uma tabela com as colunas:
Tarefa | Próxima ação (verbo concreto) | Quadrante de Eisenhower | Projeto | Estimativa em minutos | Prazo sugerido.
Regras: tarefas com menos de 2 minutos devem ser marcadas "fazer agora".
Se algo estiver vago, faça uma pergunta no final em vez de inventar.

Anotações:
[cole aqui]
```

## 2. Planejamento semanal em blocos

```
Monte meu planejamento da semana em blocos de tempo.
Compromissos fixos: [reuniões e aulas com dia e hora]
Tarefas pendentes (com estimativa): [cole a tabela]
Regras: blocos de foco de 25 minutos com pausa de 5; máximo de 6 ciclos de foco por dia;
nada depois das [19h] nos dias úteis; reservar 30 minutos na sexta para a revisão semanal;
deixar pelo menos um período livre por dia. Devolva por dia, com horário, e avise se algo não couber.
```

## 3. Quebra de tarefa grande

```
Quebre a tarefa "[descrição]" em subtarefas de 25 a 50 minutos.
Para cada uma, indique o resultado esperado e o primeiro passo de 5 minutos.
Ordene pela sequência mais lógica e diga qual é a menos agradável, para eu começar por ela.
```

## 4. Resumo de reunião

```
Resuma a transcrição abaixo em: (1) decisões tomadas, (2) responsáveis e prazos,
(3) pontos em aberto, (4) próximos passos. No máximo 10 linhas. Não invente responsáveis.

Transcrição:
[cole aqui]
```

## 5. Mensagem objetiva

```
Reescreva a mensagem abaixo no formato contexto, pedido e prazo, em no máximo 4 linhas,
tom [cordial e direto]. Mantenha os fatos e não acrescente informações.

Mensagem:
[cole aqui]
```

## 6. Revisão semanal

```
Esta é minha semana (dados do painel):
Conclusão: [x]% | Ciclos de foco: [n] | Importantes feitas: [n] | Bem-estar: [n]/5
Tarefas adiadas: [lista]
Aponte 3 padrões, 2 ajustes simples para a próxima semana e diga se devo reduzir a carga.
Seja objetivo e não me cobre de forma punitiva.
```

## 7. Rascunho de resposta a ticket

Antes de colar, remova nomes, contatos e qualquer dado do cliente ou da empresa.

```
Organize o rascunho abaixo em uma resposta de atendimento clara e educada, em no máximo 6 linhas.
Estrutura: (1) o que entendi do problema, (2) o que foi feito ou o que o cliente precisa fazer, (3) próximo passo e prazo.
Não invente informações. Se faltar algo, liste as perguntas que preciso fazer ao cliente.

Rascunho:
[cole aqui, sem dados pessoais]
```

## 8. Fechamento do dia

```
Com base nestes números do dia, escreva um registro de 3 linhas para o Notion:
tickets resolvidos: [n] | ciclos de foco: [n] | o que ficou pendente: [lista] | como me senti (1 a 5): [n].
Sugira as 3 prioridades (Big 3) de amanhã a partir dos pendentes.
```
