**Contexto**

Algumas empresas utilizam, em suas entrevistas, desafios de **resolução de problemas** de programação, como Facebook, Amazon, Apple, Netflix, Google, e recentemente, a **FORD** fez um processo seletivo em que uma etapa da entrevista era um teste nesse formato.

Nesse sentido, venho apresentar a ferramenta utilizada para rodar esse desafio da FORD. Ela chama-se **URI ONLINE JUDGE (www.urionlinejudge.com.br)**, que logo menos passará a se chamar **beecrow** , pois agora essa plataforma faz parte de uma empresa independente e por isso mudará de nome. Nela contém diversos problemas com vários níveis de dificuldade e com muitos assuntos.

**Problema**

Devido a dificuldade que muitas pessoas têm quando começam a utilizar a plataforma, o intuito aqui é explicar como ela funciona. Em outras palavras, será explicado tudo para que você inicie na plataforma com uma menor quantidade de dúvidas.

**Solução**

1. Apresentação da plataforma
2. Entrada/Saída
3. Respostas do juiz
4. Fazer um exemplo com cada entrada possível da plataforma.

**Próximos passos**

Treinar, treinar e treinar.

**Entradas e Saídas**

Existem alguns tipos de entradas e saídas nos problemas do URI, as mais comuns são:

**Entradas**

- **Casos de testes individuais:**
  - Cada caso de teste é armazenado em um único **arquivo**.

![](RackMultipart20211019-4-rfvmz6_html_1288c9b1051aa06b.png)

3 casos de testes em arquivos independentes e suas saídas esperadas.

- **Múltiplos casos de testes:**
  - Em um **arquivo** , pode haver mais de um caso de teste.

![](RackMultipart20211019-4-rfvmz6_html_bd09f9097c65af3b.png)

3 casos de teste, com suas respectivas saídas. Os múltiplos casos de teste terminam quando é fornecido o valor 0.

Além disso, há diferentes formas de tratar as entradas/saídas nesse caso de múltiplos casos de teste, sendo elas:

- O **número** de casos de teste pode ser fornecido na **primeira linha da entrada** ;
- Os casos de teste podem ser **terminados** com valores especiais, tais como **0** ou **\*** , não limitado a eles;
- Também há a possibilidade dos casos de teste terminarem em **EOF** (sigla para **end-of-file** ).

Exemplo de leitura em um caso de teste que termina em **EOF** :

_while True:_

_try:_

_...lógica..._

_except EOFError:_

_break_

**Saídas**

As saídas geralmente devem estar acompanhadas de **uma** quebra de linha, exemplo:

![](RackMultipart20211019-4-rfvmz6_html_5cd13a6af0ab37fa.png) ![](RackMultipart20211019-4-rfvmz6_html_99ec56d346bea23e.png) ![](RackMultipart20211019-4-rfvmz6_html_e21efc37d6a7c1e5.png)

CORRETOERRADOERRADO

Entretanto, no enunciado do problema estará especificado a forma correta, caso contrário, tenha como _default_ este exemplo.

**Arquivos de entrada e saída**

Apesar de lermos pela entrada padrão (ex: _value = input()_, _print(f&quot;X = {a + b}&quot;)_), por trás, na verdade, nós estaremos lendo e escrevendo em **arquivos** , por isso, também devemos ter um cuidado no trato dessas informações, exemplos:

No **Python** , quando lemos com _input()_, o mesmo fará a leitura da linha inteira. Dito isso, em um caso de teste de exemplo como:

![](RackMultipart20211019-4-rfvmz6_html_9973c440d22c431b.png)

No primeiro _input()_ será lido uma **string** com **&quot;10 7&quot;** , no segundo **&quot;C 1 10&quot;** e assim sucessivamente. Visto isso, é nítido que é necessário um tratamento desses dados. _(conversões, atribuições, etc…)._

**Como o juiz avalia**

O seu código-fonte será enviado e o sistema executará todos os casos de teste disponíveis para aquele problema e sua saída deve ser **IGUAL** a saída esperada.

Além disso, há algumas **restrições** que devem ser levadas em consideração, como o **tempo de execução e o limite de memória usado.** No exemplo abaixo o algoritmo deve passar nos casos de teste com um tempo de execução máximo de **2 segundos** e uso máximo de memória em **200MB.** Cada linguagem tem sua particularidade, então algumas possuem um tempo limite diferente, no python, por exemplo, é de **1 segundo a mais** , ou seja, no problema abaixo o tempo limite para python seria de **3 segundos**.

![](RackMultipart20211019-4-rfvmz6_html_e1c0cc17098928ce.png)

![](RackMultipart20211019-4-rfvmz6_html_1298ee9f075e6439.png)

Leitura obrigatória:

[https://www.urionlinejudge.com.br/judge/pt/faqs/about/judge](https://www.urionlinejudge.com.br/judge/pt/faqs/about/judge)

[https://www.urionlinejudge.com.br/judge/pt/faqs/about/problems](https://www.urionlinejudge.com.br/judge/pt/faqs/about/problems)

[https://www.urionlinejudge.com.br/judge/pt/faqs/about/examples](https://www.urionlinejudge.com.br/judge/pt/faqs/about/examples)
