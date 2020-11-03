# NFR Framework

<p align="justify">
O NFR Framework é uma abordagem para representar e analisar Requisitos Não-Funcionais. Seu objetivo é ajudar desenvolvedores na implementação de soluções personalizadas, levando em consideração as características do domínio e dos sistema em questão.
</p>

<p align="justify">
O Framework utiliza de softgoals, um objetivo que não possui uma clara definição nem critérios de satisfação precisos. São utilizados para representar Requisitos Não-Funcionais e podem estar inter-relacionados, expressando a influência de uma softgoal em outro.
</p>

<p align="justify">
É representado por meio de um grafo, chamado Softgoal Interdependency Graph (SIG), que registra as considerações do desenvolvedor sobre os softgoals e mostra suas interdependências.
</p>

Os softgoals podem ser separados em 3 tipos:

* NFR Softgoal – Característica abstrata, a qual se deseja considerar na análise, visando saber se a mesma será cumprida ou não cumprida, ou seja, escolhida ou não escolhida para ser implementada. São requisitos não funcionais, vistos como critérios/atributos de qualidade.

* Operationalizing Softgoal – forma concreta de viabilizar ou não as características abstratas. São funcionalidades.

* Claim Softgoal(Argumentation) – a notação que pode ser acrescentada ao modelo, argumentando algo sobre um ponto específico da modelagem. Escrita em linguagem natural.

Cada um desses Softgoals podem ser decompostos, e os tipos de decomposição são:

* Decomposição de Softgoal NFR: refina ou subdivide um um softgoal NFR em outros específicos. Isso pode ajudar a dividir grandes problemas em problemas menores e oferece um aspecto útil para lidar com ambiguidades e prioridades.

* Decomposição de Operacionalização: subdivide um softgoal de operacionalização em outros softgoals de operacionalização mais específicos. Operacionalizações são úteis para definir uma solução geral e refiná-la em soluções mais específicas.

* Decomposição de Afirmação (Claims): refina um softgoal de afirmação em outros softgoals de afirmação. Ela é importante para apoiar ou negar justificativas específicas de projeto.

* Priorização: A priorização é um tipo especial de decomposição, onde ocorre o refinamento de um softgoal em outro softgoal com o mesmo tipo e tópicos, mas com uma prioridade associada.

<p align="justify">
As decomposições são especificações dos softgoals, ou seja, alterações no estado de um softgoal filho geram alterações no softgoal pai, e essas alterações são chamadas de contribuições. Essas contribuições são:
</p>

Contribuição | Descrição
-|-
AND | se os softgoals descendentes forem satisfeitos os softgoals ascendentes também são.
OR | se algum softgoal descendente form satisfeito, o ascendente é satisfeito.
MAKE(++) | se o softgoal descendente for satisfeito o softgoal pai também é.
BREAK(--) | se o softgoal descendente for suficientemente satisfeito, o softgoal pai é negado.
HELP(+) | se o softgoal descendente for parcialmente satisfeito, o softgoal ascendente será parcialmente satisfeito.
HURT(-) | se o softgoal descendente for satisfeito, o softgoal ascendente será parcialmente negado.
UNKNOWN(?) | fornece uma contribuição desconhecida entre um softgoal descendente e um ascendente, e pode ser tanto positiva quanto negativa.
EQUALS | o softgoal descendente só será satisfeito se o softgoal ascendente for satisfeito / o softgoal descendente será negado se o softgoal ascendente for negado.
SOME (+\|-) | usado se o sinal da contribuição é conhecido, mas a extensão(parcial ou total) não é. 

<br>
<p align="justify">
Por fim, para a análise dos softgoals, são atribuídos rótulos que definem o grau de satisfação de um softgoal. Ao atribuir um rótulo em um softgoal de baixo nível, é feita a propagação da satisfação daquele requisito de acordo com as contribuições definidas.
</p>


## NFR's

### NFR de Usabilidade

<p align='center'>Figura 01 - NFR Usabilidade</p>

![Usabilidade](https://user-images.githubusercontent.com/38164895/97350801-aabece80-186f-11eb-9d8b-8188c2960635.png)

<p align='center'>Fonte: Autor</p>

### NFR de Portabilidade

<p align='center'>Figura 02 - NFR Usabilidade</p>

![Portabilidade](https://user-images.githubusercontent.com/38164895/97351460-8c0d0780-1870-11eb-842b-dedc4df1ec95.png)

<p align='center'>Fonte: Autor</p>

### NFR de Disponibilidade

<p align='center'>Figura 03 - NFR Disponibilidade</p>

![Disponibilidade](https://user-images.githubusercontent.com/38164895/97351511-a21ac800-1870-11eb-8e6e-15d0ca5cd777.png)

<p align='center'>Fonte: Autor</p>


## Histórico de Revisões 

Autor | Versão | Data(dd/mm/aaa) | Descrição
-|-|-|-
Wagner Martins | 1.0 | 26/10/2020 | Adição das informações sobre o NFR Framework
Lucas Lopes Xavier | 1.1 | 27/10/2020 | Adição dos 3 primeiros NFR's 

## Referências

* SILVA, **Reinaldo Antônio da. NFR4ES:Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados**. Recife,  2019.

* Slides da aula 16