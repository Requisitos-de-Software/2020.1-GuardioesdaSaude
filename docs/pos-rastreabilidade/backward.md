# backward-From

## Objetivo
Este documento visa ligar todos os requisitos elicitados durante a matéria de Requisito de Software aos seus respectivos métodos de elicitação e modelagem, utilizando o método de rastreabilidade Backward-From.

- RF: Requisito Funcional
- RNF: Requisito Não Funcional
- QTN: Questionario
- INT: Instrospecção
- ST: Story Teling

## Requisitos Funcionais

| ID | Descricao | Origem | Elos |
| -- | --------- | ------ | ---- |
| 03 |Ter a opção de poder realizar seu login através de outras contas como facebook , google , etc, ou com seu email cadastrado. |  [INT](https://requisitos-de-software.github.io/2020.1-GuardioesdaSaude//elicitacao/elicitacao_tecnicas/Introspeccao/)| EF03 |
| 04 |Ter um campo para a senha cadastrada. |  [INT](https://requisitos-de-software.github.io/2020.1-GuardioesdaSaude//elicitacao/elicitacao_tecnicas/Introspeccao/)| EF04 |
| 05 |Mostrar um meio de recuperar a senha perdida. |  [INT](https://requisitos-de-software.github.io/2020.1-GuardioesdaSaude//elicitacao/elicitacao_tecnicas/Introspeccao/)| EF05 |
| 06 |Deixar claro para o usuário os Termos e Políticas do APP. |  [INT](https://requisitos-de-software.github.io/2020.1-GuardioesdaSaude//elicitacao/elicitacao_tecnicas/Introspeccao/)| EF06 |
| 07 |Perguntas específicas importantes para o app como: se ele é um profissional da saúde , se faz parte do grupo de risco e se é aluno de alguma instituição de ensino. |  [INT](https://requisitos-de-software.github.io/2020.1-GuardioesdaSaude//elicitacao/elicitacao_tecnicas/Introspeccao/)| EF07 |
| 08 |Opções de email,ou outras contas de uso do aluno, e senha |  [INT](https://requisitos-de-software.github.io/2020.1-GuardioesdaSaude//elicitacao/elicitacao_tecnicas/Introspeccao/)| EF08 |
| 09 |O sistema deverá perguntar ao usuário se ele está se sentindo bem o mal diariamente. |  [INT](https://requisitos-de-software.github.io/2020.1-GuardioesdaSaude//elicitacao/elicitacao_tecnicas/Introspeccao/)| EF09 |
| 10 |Na opção “Mal” deverá ser aberto um questionários abrangendo os sintomas sentidos e o período dos sintomas. |  [INT](https://requisitos-de-software.github.io/2020.1-GuardioesdaSaude//elicitacao/elicitacao_tecnicas/Introspeccao/)| EF10 |
| 11 |	Deverá também conter questões importantes para o momento que atual de pandemia como: “saiu de casa nos últimos 14 dias?”,”teve contato com alguém?”. |  [INT](https://requisitos-de-software.github.io/2020.1-GuardioesdaSaude//elicitacao/elicitacao_tecnicas/Introspeccao/)| EF11 |
| 12 |O sistema deve garantir que o usuário responda apenas uma vez a pergunta. |  [INT](https://requisitos-de-software.github.io/2020.1-GuardioesdaSaude//elicitacao/elicitacao_tecnicas/Introspeccao/)| EF12 |
| 13 |O usuário poderá alternar sua resposta ao longo do dia.|  [INT](https://requisitos-de-software.github.io/2020.1-GuardioesdaSaude//elicitacao/elicitacao_tecnicas/Introspeccao/)| EF13 |
| 14 |O Mapa deverá mostrar a região em que o usuário está usando o app.|  [INT](https://requisitos-de-software.github.io/2020.1-GuardioesdaSaude//elicitacao/elicitacao_tecnicas/Introspeccao/)| EF14 |
| 15 |Deverá ser informado a localização do usuário dentro da região mapeada em tempo real de uso.|  [INT](https://requisitos-de-software.github.io/2020.1-GuardioesdaSaude//elicitacao/elicitacao_tecnicas/Introspeccao/)| EF15 |
| 16 |O Mapa deverá informar de maneira clara as regiões e cidades contidas.|  [INT](https://requisitos-de-software.github.io/2020.1-GuardioesdaSaude//elicitacao/elicitacao_tecnicas/Introspeccao/)| EF16 |
| 17 |O sistema deverá nomear as ruas,vias e rodovias mostradas no mapa.|  [INT](https://requisitos-de-software.github.io/2020.1-GuardioesdaSaude//elicitacao/elicitacao_tecnicas/Introspeccao/)| EF17 |
| 18 |O sistema deverá demarcar porções no mapa indicando o grau de periculosidade delas através de cores.|  [INT](https://requisitos-de-software.github.io/2020.1-GuardioesdaSaude//elicitacao/elicitacao_tecnicas/Introspeccao/)| EF18 |
| 19 |	Ao se clicar em uma dessas porções deverá ser informado ao usuário as quantidades de pessoas ,que responderam ao app, e a porcentagem de sintomáticos.|  [INT](https://requisitos-de-software.github.io/2020.1-GuardioesdaSaude//elicitacao/elicitacao_tecnicas/Introspeccao/)| EF19 |
| 20 |	Deverá ser possível ao usuário navegar para regiões mais distantes de sua localização através do mapa exibido.|  [INT](https://requisitos-de-software.github.io/2020.1-GuardioesdaSaude//elicitacao/elicitacao_tecnicas/Introspeccao/)| EF20 |
| 21 |	Deve ser possível alterar o nome de perfil.|  [INT](https://requisitos-de-software.github.io/2020.1-GuardioesdaSaude//elicitacao/elicitacao_tecnicas/Introspeccao/)| EF21 |
| 22 |	Deve ser possível editar o nome que ficará disponível no perfil.|  [INT](https://requisitos-de-software.github.io/2020.1-GuardioesdaSaude//elicitacao/elicitacao_tecnicas/Introspeccao/)| EF22 |
| 23 |	Deve ser possível mudar e-mail e senha referente a conta.|  [INT](https://requisitos-de-software.github.io/2020.1-GuardioesdaSaude//elicitacao/elicitacao_tecnicas/Introspeccao/)| EF23 |
| 24 |	Deve existir um sistema de recompensa para outras universidades.|  [QTN](https://requisitos-de-software.github.io/2020.1-GuardioesdaSaude//elicitacao/elicitacao_tecnicas/questionario/)| EF24 |
| 25 |	Deve ser possível olhar os gráficos e dados estatísticos no próprio aplicativo .|  [QTN](https://requisitos-de-software.github.io/2020.1-GuardioesdaSaude//elicitacao/elicitacao_tecnicas/questionario/)| EF25 |
| 26 |	Deve ser corrigido os bugs dos registros diários de sáude.|  [QTN](https://requisitos-de-software.github.io/2020.1-GuardioesdaSaude//elicitacao/elicitacao_tecnicas/questionario/)| EF26 |
| 27 |O usuário deve ser informado e atualizado constantemente sobre a situação da Covid-19 no país.|  [QTN](https://requisitos-de-software.github.io/2020.1-GuardioesdaSaude//elicitacao/elicitacao_tecnicas/questionario/)| EF27 |
| 28 |	O usuário deve ser notificado várias vezes ao dia, com mensagens diferentes, para reportar o seu status de saúde.   |  [QTN](https://requisitos-de-software.github.io/2020.1-GuardioesdaSaude//elicitacao/elicitacao_tecnicas/questionario/)| EF28 |
| 29 |	Deve existir um mecanismo para verificar em quais regiões,principalmente hospitais, o usuário deva evitar caso tenha a necessidade de ir.   |  [QTN](https://requisitos-de-software.github.io/2020.1-GuardioesdaSaude//elicitacao/elicitacao_tecnicas/questionario/)| EF29 |
| 30 |	Deve ser possível reportar bugs, e problemas técnicos pertinente ao sistema.   |  [QTN](https://requisitos-de-software.github.io/2020.1-GuardioesdaSaude//elicitacao/elicitacao_tecnicas/questionario/)| EF30 |
| 31 |	O sistema tem que mostrar a quantidade de infectados em cada cidade.   |  [ST](https://requisitos-de-software.github.io/2020.1-GuardioesdaSaude/elicitacao/elicitacao_tecnicas/storytelling/)| EF31 |
| 32 |	O sistema tem que mostrar o total de infectados no DF.   |  [ST](https://requisitos-de-software.github.io/2020.1-GuardioesdaSaude/elicitacao/elicitacao_tecnicas/storytelling/)| EF32 |
| 33 |	O sistema tem que destacar as áreas mais afetadas.   |  [ST](https://requisitos-de-software.github.io/2020.1-GuardioesdaSaude/elicitacao/elicitacao_tecnicas/storytelling/)| EF33 |
| 34 |	O usuário tem que informar seu estado de saúde.   |  [ST](https://requisitos-de-software.github.io/2020.1-GuardioesdaSaude/elicitacao/elicitacao_tecnicas/storytelling/)| EF34 |
| 35 |	O usuário tem que informar sua cidade.  |  [ST](https://requisitos-de-software.github.io/2020.1-GuardioesdaSaude/elicitacao/elicitacao_tecnicas/storytelling/)| EF35 |
| 36 |	O sistema deve mostrar gráficos contendo o estado de saúde de cada usuário.  |  [ST](https://requisitos-de-software.github.io/2020.1-GuardioesdaSaude/elicitacao/elicitacao_tecnicas/storytelling/)| EF36 |
| 37 |	O sistema deve exibir um mapa mostrando as áreas mais afetadas. |  [ST](https://requisitos-de-software.github.io/2020.1-GuardioesdaSaude/elicitacao/elicitacao_tecnicas/storytelling/)| EF37 |
| 38 |		O sistema poderia exibir a faixa etária dos infectados. |  [ST](https://requisitos-de-software.github.io/2020.1-GuardioesdaSaude/elicitacao/elicitacao_tecnicas/storytelling/)| EF38 |





## Requisitos Não-Funcionais
| ID | Descricao | Origem | Elos |
| -- | --------- | ------ | ---- |
| 01 | Ter uma tela agradável, limpa e intuitiva com as opções de cadastro e Login. |  [INT](https://requisitos-de-software.github.io/2020.1-GuardioesdaSaude//elicitacao/elicitacao_tecnicas/Introspeccao/)| EF01 |
| 02 | Acesso fácil às diversas telas do app. |  [INT](https://requisitos-de-software.github.io/2020.1-GuardioesdaSaude//elicitacao/elicitacao_tecnicas/Introspeccao/)| EF02 |