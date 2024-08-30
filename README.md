Lista de Exercícios Manipulação de DOM
Exercício 1: Interação com Eventos
Descrição: Crie uma página com um campo de texto (<input type="text">) e um botão. Ao clicar no botão, exiba uma mensagem que depende do conteúdo digitado no campo de texto.
Tarefas:
Capture o evento de clique no botão.
Use value para obter o texto digitado no campo de texto.
Exiba uma mensagem abaixo do campo de texto com base no valor inserido.
Exercício 2: Calculadora Simples
Descrição: Crie uma calculadora básica que permita ao usuário inserir dois números e selecionar uma operação (adição, subtração, multiplicação, divisão). Ao clicar em "Calcular", o resultado deve ser exibido na tela.
Tarefas:
Crie inputs para receber os dois números e um dropdown para selecionar a operação.
Use addEventListener para capturar o clique no botão "Calcular".
Realize a operação matemática selecionada e exiba o resultado.
Valide os inputs para garantir que os valores inseridos são números.
Exercício 3: Lista de Tarefas
Descrição: Crie uma página que funcione como uma lista de tarefas (to-do list). O usuário deve poder adicionar novas tarefas, marcar tarefas como concluídas e remover tarefas da lista.
Tarefas:
Use um campo de texto para inserir novas tarefas e um botão para adicionar a tarefa à lista.
Adicione um botão "Excluir" próximo a cada tarefa que permita removê-la.
Adicione um botão "Concluir" que permita riscar a tarefa, indicando que foi concluída.
Use localStorage para salvar a lista de tarefas, para que elas permaneçam ao recarregar a página.
Exercício 4: Galeria de Imagens
Descrição: Crie uma galeria de imagens que exibe miniaturas de várias imagens. Ao clicar em uma miniatura, a imagem completa deve ser exibida em destaque na página.
Tarefas:
Crie uma série de imagens pequenas (miniaturas) e use querySelectorAll para selecioná-las.
Use um evento de clique para exibir a imagem completa em uma área maior na página.
Estilize a galeria para que as miniaturas fiquem alinhadas e a imagem em destaque fique centralizada.
Exercício 5: Jogo de Adivinhação
Descrição: Crie um jogo de adivinhação onde o usuário tenta adivinhar um número gerado aleatoriamente entre 1 e 100. O jogo deve fornecer dicas se o palpite está muito alto ou muito baixo, e deve indicar quando o usuário acertou.
Tarefas:
Use Math.random() para gerar um número aleatório entre 1 e 100.
Crie um campo de input para que o usuário insira seu palpite e um botão para enviar.
Mostre mensagens que indicam se o palpite está alto, baixo ou correto.
Permita que o jogo reinicie após o acerto, com a opção de gerar um novo número aleatório.

Exercício 6: Manipulação de Classes
Descrição: Crie uma página com três divs, cada uma com uma cor de fundo diferente. Adicione um botão que, ao ser clicado, troca a classe das divs, alterando sua aparência (cor de fundo).
Tarefas:
Use classList.add() para adicionar uma nova classe a uma das divs.
Use classList.remove() para remover uma classe de outra div.
Utilize classList.toggle() para alternar uma classe em uma terceira div.
