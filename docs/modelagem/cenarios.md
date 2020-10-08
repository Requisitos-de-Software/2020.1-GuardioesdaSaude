# Cenários

É uma estratégia reconhecida para compreender as interações entre ambientes e sistemas, assim como elicitar a parte comportamental do software, sua dinâmica e/ou seu fluxo.

Cada cenário geralmente cobre um pequeno número de interações possíveis, e oferecem diversos tipos de informação em diferentes níveis de detalhamento.



**Realizar cadastro**

|Objetivo  |
 -----------   |
|Permitir que os usuários se cadastrem |
|**Contexto** |
|Local: Tela inicial,clicando no segundo botão para se cadastrar <br>Pré-Condição: Ter instalado o app<br>Pós-Condição: realiza inscrição<br> |
|**Atores**|
|Usuário que deseja ter cadastro no aplicativo|
|**Recursos**|
|Internet, aplicativo, conta de e-mail|
|**Episódios**|
|Usuário deseja reportar seu estado de saúde<br>Usuário navega até a página Home<br>Clica em algum dos botões "BEM" ou "MAL"<br>Se a opção selecionada for bem, o aplicativo salva o estado de saúde<br>Se caso for MAL, pede mais informações e em seguida, salva as informações<br>|
|**Restrição**|
|possuir um e-mail|
|**Exceção**|
|Estar offline <br> E-mail inválido<br>Aplicativo estar indisponível<br>Senha inválida<br>Conta já existente<br>


## [C2](#c2)

**Fazer login**

|Objetivo  |
 -----------   |
|Fazer Login no aplicativo|
|**Contexto** |
|Local: Tela inicial deve clicar no botão login<br>Pré-Condição: Ter o app instalado<br>Pós-Condição: Usuário faz login |
|**Atores**|
|Usuário  que deseja fazer login e já fez inscrição|
|**Recursos**|
|Internet, aplicativo, e-mail válido, senha válida|
|**Episódios**|
|Usuário clica no botão "login" na tela inicial. Em seguida, inserir os dados de login <br> estará logado|
|**Restrição**|
|Usuário ter o aplicativo<br> Usuário possuir cadastro|
|**Exceção**|
|Internet cair<br>Usuário esquecer e-mail<br>Usuário esquecer a senha|

## [C3](#c3)

**Reportar estado de saúde**


|Objetivo  |
 -----------   |
|Reporta estado de saúde|
|**Contexto** |
|Local: Tela Home deve clicar no botão "BEM" ou MAL"<br>Pré-Condição: Ter o app instalado<br>Pós-Condição: Usuário registra o estado de saúde |
|**Atores**|
|Usuário  que quer reportar o seu estado de saúde|
|**Recursos**|
|Internet, aplicativo|
|**Episódios**|
|Usuário quer reportar o seu estado de saúde abre o aplicativo<br><br> Usuário clica no botão "BEM" é referente ao seu estado de saúde normal. <br> Usuário clica no botão "MAL" na tela home. Em seguida, responde mais perguntas sobre os sintomas. <br> O sistema salva a opção reportarda.|
|**Restrição**|
|Usuário ter o aplicativo instalado.<br> Usuário estar logado|
|**Exceção**|
|Internet cair<br> Usuário ja ter reportado naquele dia <br> Usuário não logado <br> Sistema indisponível|


## Histórico de revisões

Autor | Versão | Data(dd/mm/aaaa) | Descrição 
------|--------|------------------|----------
Wagner Martins | 1.0 | 01/10/2020 | Informações sobre cenários
Lucas Lopes | 2.0 | 08/10/2020 | Cenários: C1,C2 e C3



## Referências

SOMMERVILLE, Ian. **Engenharia de Software**. Pearson Prentice Hall. ed. 9. São Paulo, 2011.
