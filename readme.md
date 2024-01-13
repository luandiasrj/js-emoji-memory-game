## Jogo da memória simples usando VanillaJS

Bem-vindo ao **Jogo da memória**! Neste repositório, você encontrará um jogo divertido de memória. Este projeto não apenas oferece entretenimento, mas também demonstra várias técnicas avançadas de desenvolvimento de jogos em JavaScript.

### Tecnologias Utilizadas

- HTML5 e CSS3 para a estrutura e aparência do jogo.
- JavaScript para a lógica de programação e interatividade.

### Funcionalidades Incríveis

### Como Jogar

Acesse: [https://luandiasrj.github.io/js-emoji-memory-game/](https://luandiasrj.github.io/js-emoji-memory-game/)

1. Clique nas cartas com a mesma figurinha.

### Melhorias

- **Embaralhamento de emojis:** Substituída a função `sort()` do JavaScript, pois não é a melhor maneira de embaralhar um array. Ela pode não fornecer uma distribuição uniforme, o que levava a um embaralhamento inadequado dos emojis.

- **Manipulação de eventos:** Se um usuário clicasse rapidamente e abrisse mais de duas cartas antes que a função `setTimeout` fosse executada, isso poderia levar a um comportamento inesperado. A solução foi desabilitar todos os cliques até que a verificação seja concluída.

- **Falta de limpeza de eventos:** O código não removia o manipulador de eventos das cartas correspondentes. Isso significa que um usuário poderia clicar nas mesmas cartas correspondentes novamente, o que pode levaria a um comportamento inesperado.

### Contribuição

Contribuições são bem-vindas! Se você deseja melhorar este jogo, adicionar novos recursos ou corrigir problemas, sinta-se à vontade para abrir um _pull request_.

### Créditos

Este jogo foi desenvolvido como parte de um projeto educacional da Digital Innovation One.

---

Divirta-se jogando o **js-emoji-memory-game** enquanto explora as técnicas modernas de desenvolvimento de jogos em JavaScript. Lembre-se de conferir o repositório original [aqui](https://github.com/digitalinnovationone/js-emoji-memory-game) e deixar uma ⭐️ se você gostou do projeto!
