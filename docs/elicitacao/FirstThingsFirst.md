# First things First (FTF)

## O que é
É um método de priorização que busca identificar quais requisitos geram mais valor para o produto, baseado em operações que consideram valor(benefícios), custos e riscos.

Esse método, segundo WIEGERS (1999, p. 4), deve ser usado apenas em requisitos negociáveis, ou seja, requisitos não vitais para o produto de software.

## Como funciona

O modelo FTF segue 8 passos:

1- Listar todos os requisitos, recursos, ou casos de uso que devem ser priorizados em uma planiha. Todos os itens devem ser do mesmo nível de abstração, ou seja, não se deve misturar requisitos e recursos. Caso requisitos sejam logicamente relacionados, apenas o principal requisito deve ser incluído.

2- Estimar o benefício relativo de cada requisito em uma escala de 1 a 9, em que 1 indica poucos benefícios e 9 o maior benefício possível.

3- Estimar a penalidade relativa a qual o cliente ou o negócio sofreria caso o requisito não seja implementado. Também é usada uma escala de 1 a 9, onde 1 significa que não há penalidade e 9 indica uma penalidade muito séria.

4- Calcular a soma relativa entre benefícios e penalidades. Por padrão, os dois têm pesos iguais, porém podem ser refinados ao mudar os pesos dos dois fatores.

5- Estimar o custo de implementação relativo de cada requisito. Novamente de 1 a 9, sendo 1 o custo mais baixo, e 9 o mais alto.

6- Os desenvolvedores estimam o grau relativo de riscos associados com o recurso em uma escala de 1 a 9. 1 significa que pode ser programado de olhos fechados, 9 indica preocupações sérias sobre viabilidade, disponibilidade de equipe ou mesmo falta de experiência com novas ferramentas ou técnologias.

7- Uma vez com as estimativas estão na planilha, são calculadas a prioridade de cada requisito. A fórmula para esse cálculo é
prioridade = valor % / (custo % * peso_custo + risco % * peso_risco)

8- Ordene a lista em ordem descendente(da maior para a menor) de acordo com a prioridade. Os requisitos no topo da lista devem ter o melhor balanço entre valor, custo e risco, e por isso devem ter maior prioridade de implementação. O cliente chave e os representantes dos desenvolvedores devem revisar a planilha.

Obs.: As colunas com porcetagem (%) são uma representação do quanto dado requisito pesa em relação ao total. Por exemplo, Custo % é calculado como: 
(Custo relativo do requisito / total do Custo relativo) * 100
e a soma total desta coluna deve ser igual a 100.

## First Things First: Guardiões da Saúde

|ID             |Requisito                                                                                                                                                                              |Benefício relativo|Penalidade relativa|Valor total|Valor %|Custo relativo|Custo %|Risco relativo|Risco %|Prioridade|
|:-------------:|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:----------------:|:-----------------:|:---------:|:-----:|:------------:|:-----:|:------------:|:-----:|:--------:|
|20             |Deverá ser possível ao usuário navegar para regiões mais distantes de sua localização através do mapa exibido.                                                                         |4                 |6                  |10         |4,76   |1             |2,04   |1             |3,03   |1,33913   |
|21             |Deve ser possível alterar o nome de perfil.                                                                                                                                            |6                 |7                  |13         |6,19   |2             |4,08   |1             |3,03   |1,10608   |
|8              |(Etapa de cadastro) Opções de email,ou outras contas de uso do aluno, e senha.                                                                                                         |7                 |5                  |12         |5,71   |2             |4,08   |1             |3,03   |1,02099   |
|30             |Deve ser possível reportar bugs, e problemas técnicos pertinente ao sistema.                                                                                                           |6                 |6                  |12         |5,71   |2             |4,08   |2             |6,06   |0,80348   |
|7              |(Etapa de cadastro) perguntas específicas importantes para o app como: se ele é um profissional da saúde , se faz parte do grupo de risco e se é aluno de alguma instituição de ensino.|6                 |3                  |9          |4,29   |2             |4,08   |1             |3,03   |0,76575   |
|26             |Deve ser corrigido os bugs dos registros diários de saúde.                                                                                                                             |7                 |5                  |12         |5,71   |3             |6,12   |1             |3,03   |0,74818   |
|22             |Deve ser possível editar o nome que ficará disponível no perfil.                                                                                                                       |6                 |5                  |11         |5,24   |2             |4,08   |2             |6,06   |0,73652   |
|38             |O sistema poderia exibir a faixa etária dos infectados.                                                                                                                                |8                 |6                  |14         |6,67   |3             |6,12   |2             |6,06   |0,72838   |
|3              |Ter a opção de poder realizar seu login através de outras contas como facebook , google , etc, ou com seu email cadastrado.                                                            |6                 |2                  |8          |3,81   |2             |4,08   |1             |3,03   |0,68066   |
|33             |O sistema tem que destacar as áreas mais afetadas.                                                                                                                                     |8                 |7                  |15         |7,14   |4             |8,16   |2             |6,06   |0,63812   |
|27             |O usuário deve ser informado e atualizado constantemente sobre a situação da Covid-19 no país.                                                                                         |8                 |7                  |15         |7,14   |5             |10,20  |1             |3,03   |0,60950   |
|24             |Deve existir um sistema de recompensa para outras universidades.                                                                                                                       |8                 |6                  |14         |6,67   |1             |2,04   |6             |18,18  |0,59889   |
|23             |Deve ser possível mudar e-mail e senha referente a conta.                                                                                                                              |6                 |8                  |14         |6,67   |4             |8,16   |2             |6,06   |0,59558   |
|25             |Deve ser possível olhar os gráficos e dados estatísticos no próprio aplicativo.                                                                                                        |7                 |6                  |13         |6,19   |4             |8,16   |2             |6,06   |0,55304   |
|19             |Ao se clicar em uma dessas porções (do mapa) deverá ser informado ao usuário as quantidades de pessoas ,que responderam ao app, e a porcentagem de sintomáticos.                       |8                 |8                  |16         |7,62   |5             |10,20  |3             |9,09   |0,51656   |
|29             |Deve existir um mecanismo para verificar em quais regiões,principalmente hospitais, o usuário deva evitar caso tenha a necessidade de ir.                                              |8                 |7                  |15         |7,14   |5             |10,20  |3             |9,09   |0,48428   |
|28             |O usuário deve ser notificado várias vezes ao dia, com mensagens diferentes, para reportar o seu status de saúde                                                                       |4                 |3                  |7          |3,33   |2             |4,08   |2             |6,06   |0,46870   |
|               |Total                                                                                                                                                                                  |113               |97                 |210        |100,00 |49            |100,00 |33            |100,00 |-         |

Os pesos considerados são:

- Benefício relativo: 1
- Penalidade relativa: 1
- Custo relativo: 1
- Risco relativo: 0,5

## Histórico de Revisões
| Autor | Versão | Data(dd/mm/aaaa) | Descrição
| ---- | ----- | ---- | ----
| Wagner Martins | 1.0 | 27/09/2020 | Descrição do método e Priorização dos requisitos


## Referências

WIEGERS Karl E. **First Things First: Prioritizing Requirements**. Setembro de 1999. Disponível em: <https://www.processimpact.com/articles/prioritizing.pdf>
