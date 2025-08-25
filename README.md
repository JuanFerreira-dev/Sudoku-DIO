# Sudoku-DIO

Resolução de Sudoku em Java 🧩
Este é um projeto em Java que implementa um resolvedor de Sudoku. Ele utiliza um algoritmo de busca em profundidade (DFS - Depth-First Search) com backtracking para encontrar a solução de qualquer tabuleiro de Sudoku válido.

🧠 Lógica de Solução
O resolvedor de Sudoku utiliza uma abordagem de busca em profundidade (DFS) para explorar as possíveis soluções. A lógica principal é a seguinte:

O algoritmo começa a resolver o Sudoku preenchendo as células vazias com os valores possíveis.

Para uma célula vazia, ele tenta um dos valores possíveis e, em seguida, chama a si mesmo recursivamente para continuar a resolver o tabuleiro com essa nova configuração.

Se a chamada recursiva retornar false (indicando que a configuração atual não leva a uma solução), o algoritmo "recua" (backtracking), desfaz o último movimento e tenta o próximo valor possível para a célula.

Esse processo continua até que uma solução completa e válida seja encontrada ou até que todas as possibilidades tenham sido esgotadas, confirmando que o Sudoku não tem solução.

A classe Solution contém a lógica principal do algoritmo dfs(), que gerencia as chamadas recursivas e o processo de backtracking.

🛠️ Tecnologias e Requisitos
Linguagem: Java

Requisito: JDK 8 ou superior

🤝 Contribuições
Sinta-se à vontade para abrir uma issue ou enviar um pull request se encontrar um bug ou quiser sugerir melhorias.
