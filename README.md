# Meu Kit de IA

Desafio de Projeto da [DIO](https://dio.me): monte o seu kit de IA para o dia a dia e delegue uma tarefa real, com você no comando.

O kit foi criado pelo Expert Bruno Lima com os prompts, templates, checklists e skills usados nas Aulas. Ele não é uma apostila: abra a pasta que resolve o seu problema, copie o modelo, adapte e use.

**Copie → adapte → teste → confira → melhore**

## Como Fazer o Desafio

Você não precisa instalar nada nem saber programar. Tudo acontece no navegador.

1. Clique em **Use this template**, depois em **Create a new repository**. Dê um nome simples, como `meu-kit-de-ia`, deixe **Public** e confirme.
2. Siga os passos abaixo com uma tarefa real da sua semana.
3. Preencha a seção [Minha Entrega](#minha-entrega) da sua cópia e entregue o link dela na DIO.

## Os Passos

1. **Escolha uma tarefa real.** Comece pelo trabalho que se repete na sua semana, como preparar uma reunião ou montar um relatório, e não pela ferramenta.
2. **Pegue um modelo.** Abra a pasta do kit que combina com a sua tarefa. Cada modelo tem um botão de copiar no canto.
3. **Adapte.** Troque o que está entre colchetes pelo seu contexto, objetivo, dados, limites e formato.
4. **Teste.** A primeira resposta é um ponto de partida. Ajuste até funcionar para a sua realidade.
5. **Delegue.** Com o [template de delegação](02-templates/03-delegacao.md), entregue a tarefa à IA. Peça o plano antes de ela começar, acompanhe e valide o resultado.
6. **Confira.** Provável não é o mesmo que verdadeiro. Revise com o [Pare, Confira, Use](03-checklists/01-pare-confira-use.md) antes de usar.

## O Que Tem no Kit

| Pasta | Para que serve |
|---|---|
| [01-prompts](01-prompts) | Pedidos prontos para adaptar: escrita, comunicação, pesquisa, comparação e preparação de reuniões |
| [02-templates](02-templates) | Estruturas para preencher: bom pedido, pesquisa e decisão, e delegação |
| [03-checklists](03-checklists) | Revisão de respostas, de textos e de tarefas delegadas |
| [04-skills](04-skills) | Como criar uma skill, e a Skill Preparador de Reuniões usada nas Aulas |
| [05-delegacao-e-automacao](05-delegacao-e-automacao) | Gatilhos de automação, supervisão e checkpoints |

## Os Frameworks das Aulas

- **Bom pedido:** contexto + instrução + objetivo + formato. Quanto menos a IA precisa adivinhar, melhor você consegue avaliar a resposta.
- **Pesquisa e decisão:** pergunta → pesquisa → critérios → comparação → você. Peça fontes quando precisar de informação externa. A decisão final é sua.
- **Segurança:** pare → confira → use. Valide fatos, números, datas, fontes e contexto.
- **Atalhos reutilizáveis:** criar → testar → ajustar → salvar. Separe as instruções fixas das informações que mudam a cada uso.
- **Delegação:** objetivo + contexto + recursos + limites + sucesso. Autonomia funciona melhor quando o resultado esperado está claro.
- **Supervisão:** definir → delegar → acompanhar → validar. Em tarefas maiores, confira o plano, acompanhe os checkpoints e valide o resultado.

> A IA pode ajudar você a escrever, pesquisar, organizar e executar. A responsabilidade pelo resultado continua sendo sua.

---

## Minha Entrega

Na sua cópia, abra este README, clique no lápis (**Edit this file**) e role até aqui. Troque cada frase em itálico pelo que você fez e cole o texto dentro dos blocos já prontos. Para pôr um print, é só colar a imagem com Ctrl+V. No fim, clique em **Commit changes**.

Nada de e-mail, nome de cliente, dado da empresa, senha ou informação pessoal nos textos e nos prints.

### Minha Tarefa Real

Pedi uma rotina para consultar minha agenda e meus e-mails aos domingos, às 21h, e preparar um PDF com informações para as reuniões dos próximos sete dias. Quando não houver reuniões, quero receber um conteúdo atualizado sobre IA, com exemplos úteis para o dia a dia.


Usei o kit no geral como referência e desenvolvi os prompts com apoio do ChatGPT, adaptando-os à minha rotina.


```text
Prepare um resumo das minhas reuniões dos próximos sete dias.

Consulte minha agenda e, se houver acesso autorizado, busque nos
e-mails informações relacionadas às reuniões.

Para cada reunião, apresente:
- Data, horário e assunto.
- Objetivo identificado no convite ou nas mensagens.
- Contexto necessário para eu chegar preparado.
- Pendências e materiais que preciso revisar.
- Sugestões de perguntas para esclarecer pontos em aberto.

Diferencie informações encontradas de sugestões suas.
Não invente detalhes. Avise se não conseguir acessar alguma fonte.
Não envie mensagens nem altere minha agenda.
```

```text
Selecione um tema de inteligência artificial que possa melhorar
minha rotina de trabalho e prepare um material de estudo em
português, no nível intermediário prático.

Inclua:
- Uma explicação clara do tema.
- Um exemplo de aplicação no dia a dia.
- Um exercício que eu possa testar em até 30 minutos.
- Cuidados com privacidade e limitações.
- Links das fontes consultadas e suas datas, quando disponíveis.

Se apresentar novidades, pesquise fontes atuais e diferencie
a data da publicação da data do acontecimento.

Use exemplos fictícios, sem dados pessoais ou de clientes.
Entregue em PDF se houver recurso disponível; caso contrário,
entregue o conteúdo formatado e informe essa limitação.
```

### Minha Delegação

```text
Ajudar-me a começar a semana preparado para reuniões e manter
um aprendizado contínuo sobre inteligência artificial.

Contexto:
Nem sempre tenho reuniões agendadas. Quando não houver reuniões,
quero aproveitar o relatório semanal para aprender algo útil.

Rotina desejada:
Executar aos domingos, às 21h, no fuso America/Sao_Paulo.
O agendamento precisa ser configurado e confirmado em uma
ferramenta que ofereça esse recurso.

Recursos:
Google Agenda e Gmail, quando conectados e autorizados;
pesquisa na internet para o conteúdo de IA; geração de PDF,
quando disponível.

Tarefa:
1. Consultar a agenda dos próximos sete dias.
2. Se houver reuniões, buscar e-mails relacionados e preparar
   um resumo com contexto, pendências e perguntas sugeridas.
3. Se não houver reuniões, preparar um material sobre um tema
   atual de IA com aplicação prática.
4. Gerar um PDF organizado em português.

Limites:
Não enviar e-mails, responder convites ou alterar compromissos.
Não inventar informações nem tratar falhas de acesso como
ausência de reuniões.
Se faltar acesso a uma fonte, informar a limitação.
Não publicar informações pessoais ou profissionais no GitHub.

Critério de sucesso:
Receber um material claro, com fontes verificáveis, que me
ajude a preparar as reuniões ou testar uma aplicação de IA.
```

### O Plano da IA

Antes de começar, pedi que a IA explicasse o que havia entendido
da minha solicitação. Ela propôs consultar minha agenda, relacionar
os e-mails às reuniões e organizar um PDF com sugestões de pauta
e informações para minha preparação.

O print abaixo mostra essa proposta inicial.

<img width="1250" height="802" alt="image" src="https://github.com/user-attachments/assets/443e753a-9d59-4af9-b97c-c23ea8b33d56" />

### O Resultado

<img width="1917" height="1015" alt="image" src="https://github.com/user-attachments/assets/dc03c6ae-fc8f-4b3a-8b86-3c7b6af43c7b" />

Fiz um teste e a IA gerou um PDF. Abri o PDF e conferi se o conteúdo estava de acordo com o pedido e se os links das fontes funcionavam. Conforme minha solicitação. A rotina prevê preparar informações para reuniões ou, quando não houver compromissos, produzir um conteúdo sobre IA.

### Como Foi para Você

Aprendi a fazer pedidos mais claros à IA, definindo o objetivo, os recursos e os limites. Vi como ela pode ajudar na preparação de reuniões e no aprendizado de assuntos úteis para minha rotina.
