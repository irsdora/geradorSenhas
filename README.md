![image](https://github.com/user-attachments/assets/39fed896-81bd-40a1-81d5-0faf981244ef)


# 🎯 Projetos Python 

![image](https://github.com/user-attachments/assets/1be0d00f-93f9-4416-a666-a8d50db23a25)

<h2> 📚  Projeto 1: Gerador de senhas </h2>

- Projeto utilizando funções;
- Dentro dos parênteses estão os parâmetros;
- Arquivo .py;
- len_ pass = 8 / Tamanho de uma senha;
- Uso de duas bibliotecas: import random e import string;
- Para cada dígito que o usuário utiliza são realizados alguns processos;
- Looping utilizado: For;
- Também poderia ter sido utilizado o Looping com while;
- Uso de array com os dígitos;
- Uso do método choice;
- Projeto criado com a ajuda da documentação de Python

![image](https://github.com/user-attachments/assets/8ee65164-9ef8-4587-b657-3e681473839e)

<h2> 📚 Documentação Python 3.13.5 </h2>
https://docs.python.org/pt-br/3/
https://python-guide-pt-br.readthedocs.io/pt-br/latest/

<h2> 📚  Método choice </h2>

O método choice em Python é uma função da biblioteca padrão random usada para selecionar aleatoriamente um único elemento de uma sequência, como uma lista ou uma string.
Ele é muito utilizado em situações onde é necessário realizar sorteios, escolher itens aleatórios para jogos, amostragens, entre outros cenários.
<br>
<br>
Diferenças entre o choice, choices e sample:
<br>
random.choice	Seleciona 1 item aleatório	Não se aplica
<br>
random.choices	Seleciona vários itens (parâmetro k)	Sim
<br>
random.sample	Seleciona vários itens únicos (parâmetro k)	Não
<br>

Aplicações comuns
<br>
Sorteio de nomes, prêmios ou perguntas.
<br>
Seleção aleatória de elementos para jogos.
<br>
Criação de testes, quizzes ou amostragens estatísticas
<br>

<h2> 📚  Uso do array </h2>

O array em Python é uma estrutura de dados que armazena uma sequência de elementos do mesmo tipo, acessíveis por índices numéricos. Diferente das listas, 
que podem conter elementos de tipos variados e têm tamanho dinâmico, os arrays têm tamanho fixo após a criação e são mais restritos quanto ao tipo dos dados que armazenam.
<br>
Quando usar arrays em Python
<br>
Quando for necessário armazenar grandes quantidades de dados numéricos do mesmo tipo de forma eficiente.
<br>
Quando o tamanho da coleção de dados for fixo ou conhecido antecipadamente.
<br>
Para operações que exigem manipulação de dados numéricos com melhor desempenho que listas.

<h2> 📚  Bibliotecas random e string </h2>

As bibliotecas random e string em Python são amplamente usadas para manipulação de dados aleatórios e operações com caracteres, respectivamente.

Biblioteca random
Função principal: Gera números pseudoaleatórios e permite operações relacionadas à aleatoriedade.

Importação: import random

Principais funções:

random() — retorna um número decimal aleatório entre 0 e 1.

randint(a, b) — retorna um número inteiro aleatório entre a e b (inclusive).

choice(seq) — seleciona um elemento aleatório de uma sequência.

choices(seq, k) — seleciona k elementos aleatórios, com possibilidade de repetição.

shuffle(seq) — embaralha os elementos de uma lista in-place.

sample(seq, k) — seleciona k elementos únicos aleatórios de uma sequência.

seed(valor) — define uma semente para gerar sequências aleatórias reproduzíveis.

Aplicações: sorteios, simulações, jogos, testes, embaralhamento de listas e amostragens aleatórias.

Biblioteca string
Função principal: Fornece constantes e funções para manipulação de texto e caracteres.

Importação: import string

Principais constantes:

string.ascii_letters — todas as letras ASCII (maiúsculas e minúsculas).

string.ascii_lowercase — letras minúsculas.

string.ascii_uppercase — letras maiúsculas.

string.digits — dígitos de 0 a 9.

string.punctuation — caracteres de pontuação.

string.whitespace — caracteres de espaço em branco.

Aplicações: geração de senhas, validação e manipulação de strings, filtragem de caracteres, construção de conjuntos de caracteres para sorteios e testes.


<h2> 📚  Uso do for e while </h2>

Os comandos for e while em Python são estruturas de repetição usadas para executar um bloco de código várias vezes, mas diferem em sua lógica e casos de uso.

For loop
Uso: Ideal quando se sabe quantas vezes o loop deve rodar ou quando se quer iterar diretamente sobre uma sequência (lista, tupla, string, etc.).

Funcionamento: Percorre cada elemento da sequência, executando o bloco para cada item.

Sintaxe básica:

python
for item in sequencia:
    # bloco de código
Vantagens: Mais rápido e otimizado para iterações com número definido de repetições.


While loop
Uso: Indicado quando não se sabe o número exato de repetições e o loop deve continuar enquanto uma condição for verdadeira.

Funcionamento: Avalia uma condição booleana antes de cada iteração; o bloco é executado enquanto a condição for True.

Sintaxe básica:

python
while condição:

Vantagens: Mais flexível, permite controlar a repetição com base em condições dinâmicas.

Cuidado: Pode causar loops infinitos se a condição nunca se tornar falsa.

Casos comuns: Repetir até que uma condição específica seja atendida, como aguardar uma entrada do usuário ou monitorar um estado.

<h2> 💡 Estudos, Inspiração e Repositórios </h2>
- Projeto inspirado por guias de estudos sobre Python incríveis disponíveis no Youtube.

