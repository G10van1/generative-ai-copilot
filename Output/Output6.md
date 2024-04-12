Claro! Vou criar uma função em **Python** que faz exatamente isso. Primeiro, vou gerar um array de **1000 inteiros aleatórios** e, em seguida, vou ordená-lo. Utilizarei a função `numpy.random.randint()` para gerar os números aleatórios e o método `.sort()` para ordenar o array.

```python
import numpy as np

def gerar_e_ordenar_array():
    # Gerar 1000 inteiros aleatórios entre 1 e 1000
    random_numbers = np.random.randint(low=1, high=1001, size=1000)

    # Ordenar o array
    random_numbers.sort()

    return random_numbers

# Chamar a função e imprimir o array ordenado
array_ordenado = gerar_e_ordenar_array()
print(array_ordenado)
```

Execute o programa para obter o array de inteiros aleatórios ordenado! 🎲🔢

Origem: conversa com o Bing, 11/04/2024
(1) python - Gerar vários arrays diferentes contendo números aleatórios .... https://pt.stackoverflow.com/questions/511255/gerar-v%C3%A1rios-arrays-diferentes-contendo-n%C3%BAmeros-aleat%C3%B3rios.
(2) NumPy numpy.random.rand() Função | Delft Stack. https://www.delftstack.com/pt/api/numpy/python-numpy-random.rand-function/.
(3) Gere uma lista de números aleatórios em Python | Delft Stack. https://www.delftstack.com/pt/howto/python/generate-list-of-random-numbers-in-python/.
(4) Gerar inteiros aleatórios no intervalo em Python | Delft Stack. https://www.delftstack.com/pt/howto/python/random-integers-between-range-python/.
(5) Introdução ao NumPy: Manipulação Eficiente de Arrays em Python. https://medium.com/@jvborges25/introdu%C3%A7%C3%A3o-ao-numpy-manipula%C3%A7%C3%A3o-eficiente-de-arrays-em-python-9e472ddd515f.
(6) Como criar uma matriz de inteiros aleatórios em Python?. https://bing.com/search?q=Python+gerar+array+inteiros+1000+elementos+randomicamente.
(7) Como criar uma matriz de inteiros aleatórios em Python?. https://acervolima.com/como-criar-uma-matriz-de-inteiros-aleatorios-em-python/.
(8) Como gerar números aleatórios em Python?. https://pt.stackoverflow.com/questions/76428/como-gerar-n%C3%BAmeros-aleat%C3%B3rios-em-python.
(9) Array em Python: Como Ordenar e Classificar Dados. https://bing.com/search?q=Python+ordenar+array+inteiros.
(10) O método sort para arrays e listas em Python - freeCodeCamp.org. https://www.freecodecamp.org/portuguese/news/o-metodo-sort-para-arrays-e-listas-em-python-ordenacoes-ascendente-e-descendente-explicadas-e-com-exemplos/.
(11) Array Sort Python: Aprenda a Ordenar Arrays com Python. https://awari.com.br/array-sort-python-aprenda-a-ordenar-arrays-com-python/.
(12) python - Ordenar sequência de números a partir de um arquivo TXT .... https://pt.stackoverflow.com/questions/311463/ordenar-sequ%c3%aancia-de-n%c3%bameros-a-partir-de-um-arquivo-txt.
(13) Sorting Techniques — documentação Python 3.12.2. https://docs.python.org/pt-br/3/howto/sorting.html.