# Título do Projeto Extremamente Aesthetic ;)

## 📒 Descrição
Uma partida de xadrez fictícia criada com IA Generativa.

## 🤖 Tecnologias Utilizadas
- IA Generativa **[ChatGPT](https://chat.openai.com)** para roteirização e revisão;
- Engine de xadrez de código aberto **[Stockfish 14](https://stockfishchess.org/blog/2021/stockfish-14/)** disponível no plataforma de xadrez gratuita **[Lichess](https://lichess.org/)**;

## 🧐 Processo de Criação
Pedi para que o ChatGPT gerasse uma partida de xadrez, com três condições:
1. Deveria simular o embate entre dois jogadores experientes;
2. A abertura usada deveria ser uma variante da Defesa Siciliana;
3. A partida deveria terminar em uma vitória rápida do Primeiro Jogador (o que usa as peças brancas).
Analisei o resultado na plataforma do Lichess para avaliar se os lances fazem sentido, corrigir possíveis erros de notação, e talvez fazer pequenas alterações para que realmente pareça uma partida jogada entre humanos.

## 🚀 Resultados
A primeira partida gerada pelo ChatGPT não continha erros de notação, mas o Segundo Jogador (o que usa as peças pretas) comete um erro grosseiro no lance 13, que, apesar de seguir uma certa lógica, dificilmente seria cometido por um jogador experiente. Portanto, pedi para que a IA gerasse uma nova partida, usando outra variante da mesma defesa.

O resultado foi uma partida que inicialmente tem uma melhor qualidade, mas cujos 6 ou 7 últimos lances não fazem sentido, e que resulta ainda numa posição perdedora para as brancas, apesar de a IA declarar a desistência do oponente.

Minha abordagem então foi de utilizar os 20 primeiros lances da segunda partida e alterar o final, concluindo-a com uma combinação que seria facilmente vista por um jogador razoavelmente experiente.

## 💭 Reflexão
Em áreas que exigem um conhecimento mais técnico parece ainda ser difícil fazer com que uma IA generativa simule uma criação humana. No entanto, esse problema pode ser em certa parte contornado inserindo mais especificações, e dando alguns retoques no resultado final. 
