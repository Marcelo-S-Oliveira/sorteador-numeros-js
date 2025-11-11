Sorteador de Números

Aplicação web simples e intuitiva para sortear números aleatórios dentro de um intervalo definido pelo usuário.
Desenvolvido em HTML, CSS e JavaScript, com validações robustas e exibição organizada dos resultados (10 números por linha).

Funcionalidades

✔️ Sorteio de números aleatórios sem repetição
✔️ Limite configurado pelo usuário: quantidade, número inicial e número final
✔️ Validações automáticas (intervalo incorreto, quantidade maior que o permitido etc.)
✔️ Exibição dos números em blocos de até 10 por linha
✔️ Botão de “Reiniciar” que limpa tudo e volta ao estado inicial
✔️ Interface moderna e responsiva

Tecnologias Utilizadas

HTML5
CSS3
JavaScript

📂 Estrutura do Projeto
/
├── index.html
├── style.css
├── app.js
└── img/
     ├── cachorro.png
     ├── code.png
     └── Ruido.png

▶️ Como Usar

Informe a quantidade de números a serem sorteados. Defina o intervalo: Do número → Até o número.
Clique em Sortear. Veja os resultados aparecerem organizadinhos por linha. Clique em Reiniciar para começar de novo.

🧠 Lógica do Sorteio

O sistema: Gera números aleatórios com Math.random(), Garante que não haja repetição,
Agrupa automaticamente em lotes de 10 números por linha. Atualiza o botão de Reiniciar dinamicamente.

🖼️ Demonstração

(Você pode adicionar aqui prints da interface depois)
Exemplo:

Números sorteados:
3, 8, 12, 25, 41, 77, 90, 101, 203, 299
4, 15, 18, 44...

