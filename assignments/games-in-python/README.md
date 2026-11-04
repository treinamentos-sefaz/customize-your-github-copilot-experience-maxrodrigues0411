
# 📘 Assignment: Jogo da Forca

## 🎯 Objective

Pratique manipulação de strings, loops, condicionais e seleção aleatória ao implementar um jogo da forca em Python. O jogador deve descobrir uma palavra oculta antes de esgotar as tentativas.

## 📝 Tasks

### 🛠️ Preparar a Palavra e o Estado do Jogo

#### Descrição
Selecione uma palavra aleatória da lista fornecida em `starter-code.py` e prepare as variáveis necessárias para acompanhar o andamento da partida.

#### Requisitos
O programa concluído deve:

- Selecionar uma palavra aleatoriamente da lista predefinida.
- Acompanhar as letras já tentadas e o número de palpites incorretos.
- Permitir até 6 palpites incorretos.
- Exibir cada letra ainda não descoberta como `_`, mantendo visíveis as letras corretas nas suas posições.

### 🛠️ Implementar os Palpites e o Encerramento

#### Descrição
Implemente o loop principal para receber palpites, atualizar o progresso e encerrar a partida com o resultado correspondente.

#### Requisitos
O programa concluído deve:

- Solicitar uma letra ao jogador e aceitar a entrada sem diferenciar maiúsculas de minúsculas.
- Desconsiderar entradas que não sejam uma única letra e avisar quando uma letra já tiver sido tentada.
- Atualizar o progresso quando o palpite estiver na palavra e reduzir as tentativas restantes somente para um palpite incorreto novo.
- Mostrar o progresso e as tentativas incorretas restantes a cada rodada.
- Encerrar quando todas as letras forem descobertas ou quando os 6 palpites incorretos forem usados.
- Exibir uma mensagem de vitória ou derrota; em caso de derrota, revelar a palavra oculta.