# Calculadora em Python e Shell Script

Este repositório contém duas versões de uma calculadora simples: uma em Python e outra em Shell Script.

## 📌 Calculadora em Python (`calculadora.py`)

O script em Python recebe dois números do usuário através do comando `input()` e os converte para `float`, permitindo cálculos com casas decimais. Em seguida, o usuário escolhe uma operação matemática (soma, subtração, multiplicação ou divisão), e uma estrutura condicional `if/elif` realiza o cálculo correspondente. O resultado é exibido na tela com o comando `print()`. Há também uma proteção contra divisão por zero, que exibe uma mensagem de erro em vez de travar o programa.

### Como executar:
```bash
python3 calculadora.py
```

## 📌 Calculadora em Shell Script (`calculadora.sh`)

O script em Shell utiliza o comando `read` para receber os dois números e a operação escolhida pelo usuário. Uma estrutura `case` verifica qual operação foi selecionada, e o comando `bc` realiza o cálculo (já que o Bash não processa operações matemáticas, principalmente decimais, nativamente). O resultado é exibido com `echo`.

### Como executar:

1. Dê permissão de execução ao arquivo:
```bash
chmod 744 calculadora.sh
```

2. Execute o script:
```bash
./calculadora.sh
```

3. Digite os dois números e a operação desejada quando solicitado.
