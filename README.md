# Desafio KNN | Word Snap

Um jogo rápido e interativo para testar o reconhecimento de palavras em inglês.
40 segundos. Zero pressão. Só precisa de reflexo.

## Sobre o projeto
O Word Snap é uma experiência gamificada desenvolvida para a campanha Black November da KNN Idiomas.
O objetivo é simples: identificar palavras em inglês de acordo com diferentes categorias, acumulando pontos e tentando alcançar a maior pontuação possível antes que o tempo acabe.

## Como jogar
1. Clique em **Jogar agora**.
2. Leia a missão apresentada na tela.
3. Selecione as palavras em inglês que correspondem à categoria.
4. Acerte o máximo de palavras possível em 40 segundos.
5. Confira seu resultado e desafie um amigo.

### Regras
- Cada partida dura 40 segundos.
- Respostas incorretas retiram 2 segundos do cronômetro.
- Acertos geram pontos e sequências de combo.
- Ao final, o jogo apresenta sua pontuação, quantidade de acertos, melhor combo e precisão.

## Tecnologias utilizadas:
- HTML5
- CSS3
- JavaScript
- Google Fonts
O projeto utiliza tecnologias nativas, sem frameworks ou dependências de instalação.

## Como executar:
Não é necessário instalar nada.
1. Baixe ou clone este repositório.
2. Abra o arquivo `index.html` em um navegador.
3. O jogo estará pronto para funcionar.

## Publicação
O projeto pode ser hospedado em plataformas de hospedagem estática, como o Netlify.
Basta enviar o arquivo `index.html` ou a pasta do projeto para realizar a publicação.

## Personalização
As principais configurações do jogo estão concentradas no objeto `CONFIG`, dentro do JavaScript:
- `COMMUNITY_URL`: endereço do grupo de WhatsApp da campanha.
- `SHARE_URL`: endereço público utilizado no convite para desafiar amigos. Se permanecer vazio, o jogo utiliza o próprio endereço da página.
- `DURATION`: duração da partida, em segundos.
- `PENALTY`: tempo descontado a cada erro.
As missões e palavras utilizadas também podem ser editadas no objeto `missions`.

## Autoria
Desenvolvido por **Eduardo Magno de S. Ferreira**.
Para a KNN Idiomas - Bucarein, da marca KNN Idiomas Brasil LTDA
