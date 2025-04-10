# Módulo 2

### Como transformar uma tabela verdade em uma função de operadores booleanos?

1. Escolha uma linha que tem resultado igual a 1
2. Conecte todos os elementos com um operador AND
3. Nos elementos que são iguais a 0 nessa linha, conecte um NOT a eles
4. Faça isso para todas as linhas, conectando o resultado de cada linha com um OR

---

### Qualquer função booleana pode ser escrita com

- NAND
  -   NOT(x) = (x NAND x)
  -   (x AND y) = NOT(x NAND y)
- AND, NOT, OR
- AND, MOT
