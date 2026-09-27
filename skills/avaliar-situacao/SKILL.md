---
name: avaliar-situacao
description: Use quando o cliente descreve algo suspeito (mensagem, ligação, link, site, transação) e quer saber se é golpe ou se é seguro.
---

# Skill: Avaliar Situação Suspeita

Ajuda o cliente a analisar uma situação potencialmente perigosa, sem dar um diagnóstico definitivo.

## Quando usar

O cliente recebeu uma mensagem, ligação, e-mail ou link e quer saber se é confiável. Ou percebeu algo estranho em uma transação ou contato.

## Processo

### 1. Entenda o que aconteceu

Peça ao cliente para descrever a situação. Não peça dados sensíveis (senha, token, código). Pergunte apenas o necessário: o que recebeu, por qual canal, o que foi solicitado.

### 2. Consulte a cartilha

Leia `agent/knowledge/cartilha-seguranca.md` e verifique se a situação descrita se encaixa em algum dos golpes mapeados. Compare os sinais de alerta.

### 3. Identifique sinais de risco

Liste os sinais de alerta presentes na situação. Explique cada um de forma simples, mostrando por que aquele sinal pode indicar uma tentativa de golpe.

### 4. Oriente sem diagnosticar

Nunca afirme "isso é golpe" nem "isso é seguro". Em vez disso, diga algo como: "Essa situação tem alguns sinais que costumam aparecer em tentativas de golpe." Apresente a orientação de segurança adequada.

### 5. Indique a ação mais segura

Dê passos concretos e simples. A ação mais importante deve vir primeiro. Se a situação envolve risco imediato, oriente o cliente a interromper a ação e procurar os canais oficiais do banco.

### 6. Verifique o entendimento

Confirme se o cliente entendeu o que deve fazer. Ofereça ajuda adicional se necessário.

## Lembre-se

- Nunca garanta que algo é seguro ou é golpe. Eduque sobre os sinais.
- Nunca peça credenciais para "verificar" a conta.
- Se o cliente já compartilhou dados sensíveis, ative a skill `orientar-incidente`.
