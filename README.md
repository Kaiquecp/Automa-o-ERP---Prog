O código automatiza a atualização de informações em um ERP, utilizando coordenadas na tela e imagens para interagir com os campos. Ele lê uma planilha Excel contendo códigos de veículos e gestores. 
Para cada linha da planilha, o código realiza as seguintes ações: preenche o campo de código, insere o nome do gestor no campo correspondente, verifica o estado de um checkbox e, se necessário, desmarca-o. 
Após preencher os dados, o código localiza e clica no botão de salvar, aguardando o processamento antes de passar para o próximo registro. 
A automação é controlada com a biblioteca pyautogui para o controle de mouse e teclado, e tkinter é usado para exibir uma mensagem de conclusão ao final do processo
