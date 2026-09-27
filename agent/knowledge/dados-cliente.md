# Dados do Cliente

Este arquivo explica como usar os dados do cliente para contextualizar as orientações de segurança.

## Arquivos disponíveis

| Arquivo | Formato | Para que serve |
|---------|---------|----------------|
| `data/perfil_investidor.json` | JSON | Adaptar o tom e a complexidade da explicação ao perfil do cliente |
| `data/historico_atendimento.csv` | CSV | Contextualizar interações anteriores, identificando se o cliente já passou por situações de segurança |
| `data/transacoes.csv` | CSV | Analisar padrões de uso para oferecer dicas de segurança contextualizadas |

## Como usar os dados

### Perfil do cliente

Leia o arquivo `data/perfil_investidor.json` para entender o perfil do cliente. Use essas informações para adaptar a complexidade das explicações. Por exemplo, se o cliente tem baixa familiaridade digital, use analogias simples do dia a dia.

**Importante:** Esse arquivo contém dados financeiros do cliente. Não use esses dados para recomendar investimentos. Use apenas para ajustar o tom da comunicação.

### Histórico de atendimento

Leia o arquivo `data/historico_atendimento.csv` para verificar se o cliente já teve atendimentos anteriores, especialmente os relacionados ao tema "Segurança". Use esse contexto para reforçar orientações relevantes de forma amigável, sem repetir informações que o cliente já demonstrou conhecer.

### Transações

Leia o arquivo `data/transacoes.csv` para identificar padrões de uso. Por exemplo, se o cliente faz muitas transações via Pix, você pode oferecer dicas específicas sobre segurança no Pix.

## Regras sobre dados

- Use somente os dados disponíveis nos arquivos listados acima.
- Nunca invente dados sobre o cliente.
- Nunca revele dados de outros clientes.
- Nunca solicite credenciais (senha, token, código de autenticação).
- Não peça dados bancários sensíveis desnecessariamente.
- Ao citar dados do cliente em exemplos, minimize a exposição de informações sensíveis.
- Nunca trate o fato de possuir um dado como autorização para realizar uma operação financeira.
