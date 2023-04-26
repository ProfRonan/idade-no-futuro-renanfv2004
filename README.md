# Idade no Ano Futuro

O script principal de vocês deve estar no arquivo `main.py`.

## 📝 Instruções 📝

No `main.py`, escreva instruções para receber os valores abaixo na seguinte ordem:

- receber do usuário um número que é a o ano atual.
- receber do usuário sua idade atual.
- receber do usuário outro número representando outro ano.
- receber do usuário o seu nome.

O programa deve fazer os cálculos para imprimir na tela a frase `Fulano, no ano de XXXX você terá YYYY anos`, com os valores corretos.

## 🧑‍💻 Exemplo de Execução 🧑‍💻

Usuário digita:

```
2010
15
2023
Fulano
```

O programa deve imprimir na tela:

```
Fulano, no ano de 2023 você terá 28 anos
```

## 🧪 Testes Automáticos 🧪

Para testar automaticamente o programa **antes** de fazer um commit e enviar o seu trabalho existem algumas formas de fazer isso.

1. executar o módulo `unittest` direto no terminal.
   Para isso, basta executar o seguinte comando:

```bash
python -m unittest
```

2. executar o arquivo `test_main.py` no terminal.
   Para isso, basta executar o seguinte comando:

```bash
python test_main.py
```

3. caso você esteja usando o [VSCode](https://code.visualstudio.com/), você pode abrir a paleta de comandos `CTRL+SHIFT+P` e digitar `Run All Tests`.
4. no seu editor de código, você pode executar o arquivo `test_main.py` e verificar o resultado dos testes no terminal.

## 🤖 Observações Importantes 🤖

- **Não altere o nome dos arquivos**. Os arquivos `test_main.py` e `main.py` precisam ter esses nomes para que os testes funcionem.
- **Não altere o nome das funções**. Os testes dependem que as funções tenham os nomes especificados no enunciado ou já escritos nos arquivos.
- **Não altere o nome dos parâmetros**. Os testes dependem que as funções tenham os parâmetros especificados no enunciado ou já escritos nos arquivos.
- **Antes de fazer um commit**, execute os testes usando um dos métodos acima para verificar se o seu programa está funcionando corretamente.
- **Caso não consiga corrigir os erros**, entre em contato com o professor ou monitores para que eles possam te ajudar.
  Para isso você deve fazer um commit com o seu trabalho incompleto e abrir uma **issue** no repositório do exercício explicando o seu problema.
