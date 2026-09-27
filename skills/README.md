# Skills da Cybele

## O que é uma skill

Uma **skill** é um guia passo a passo que ensina a Cybele a executar uma tarefa específica de forma consistente. Em vez de improvisar, a skill dá um processo claro a seguir.

Cada skill fica em uma pasta com um arquivo `SKILL.md`. Esse formato segue o padrão aberto de skills para agentes, então funciona em diferentes harnesses.

## Como a Cybele usa as skills

O cliente não precisa "chamar" a skill. Basta conversar de forma natural. A Cybele identifica a necessidade e aplica a skill certa automaticamente.

Por exemplo, se o cliente diz "recebi uma mensagem estranha do banco", a Cybele usa a skill de avaliar situação.

## Skills disponíveis

| Skill | Para que serve | Exemplo de pergunta do cliente |
|-------|----------------|-------------------------------|
| [avaliar-situacao](avaliar-situacao/SKILL.md) | Analisar uma situação suspeita reportada pelo cliente | "Recebi um SMS dizendo que meu cartão foi bloqueado. É verdade?" |
| [explicar-seguranca](explicar-seguranca/SKILL.md) | Explicar um conceito de segurança digital | "O que é phishing?" |
| [orientar-incidente](orientar-incidente/SKILL.md) | Orientar após o cliente ter sido vítima ou suspeitar de um golpe | "Acho que caí num golpe, o que eu faço?" |

## Como criar uma nova skill

1. Crie uma pasta dentro de `skills/` com um nome curto e descritivo.
2. Adicione um arquivo `SKILL.md` com o cabeçalho e o processo (siga o modelo das skills existentes).
3. Adicione a skill na tabela de `AGENTS.md` para a Cybele saber quando usá-la.
