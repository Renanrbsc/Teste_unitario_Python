# testes_unitarios

    # Pycharm por padrão, permite que você execute cada teste através de uma interface que ele possui,
    você da play no test e pode debugar caso necessário.

    # Vscode é necessário baixar a extensão "Test Explorer UI" e após instalado, realizar a seguinte        configuração:
        aperte as teclas "Ctrl" + "shift" + "p" 
        procure por:   Python:Configure Tests
        escolha a opção:   Unittest
        escolha a opção:   .    (referente ao root directory)
        escolha a opção:   test_*.py  (ele coletará todos os arquivos que comecem com test_)
    
        Arquivos de testes e métodos de testes, por padrão iniciam com test_
        O framework unittest não entenderá como um teste, os métodos que não começarem com test_

        Após configurar, aparecerá no canto esquerdo do Vscode, um símbolo de Erlenmeyer (vulgo vidro das aulas de quimica, para fazer misturas).

        Através dele você pode rodar todos os seus testes através de um botão de player.
        Também temos um botão para debugar.

        Ou podemos também ir no método de teste que estamos querendo executar, os botões de player e debug também aparecerão lá.