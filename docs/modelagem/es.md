# Especificação Suplementar

## Introdução
A Especificação Suplementar é um documento que contém a descrição de todos os requisitos não funcionais de um sistema. <br/>

## Finalidade
A finalidade deste documento é definir todos os requisitos não funcionais do aplicativo Guardiões da Saúde que, juntamente com o modelo de casos de uso, possibilitam a captura de um conjunto completo de requisitos do sistema. <br/>

## Escopo
O objetivo do aplicativo Guardiões da Saúde é detectar surtos e emergências na saúde pública através da coleta diária de dados sobre o estado de saúde dos usuários. Além disso, disponibiliza a visualização do histórico de saúde do usúario, dicas de saúde e um mapa mostrando o estado de saúde de todos os usuários da região. <br/>

## Visão Geral
Este documento apresenta especificações dos requisitos não funcionais orientado pelo FURPS+ e seu objetivo é expor os requisitos suplementares distribuídos em Funcionalidade, Usabilidade, Confiabilidade, Desempenho, Suportabilidade, Requisitos de Implementação, Requisítos Físicos e Requisitos de Licenciamento. <br/>


## Requisitos Não-Funcionais

| ID | Descrição | 
| ---- | --- |
| 1 | Ter uma tela agradável, limpa e intuitiva com as opções de cadastro e Login |
| 2 | Acesso fácil às diversas telas do app |
| 16 | O Mapa deverá informar de maneira clara as regiões e cidades contidas. |
| 12 | O sistema deve garantir que o usuário responda apenas uma vez a pergunta. |
| 17 | O sistema deverá nomear as ruas, vias e rodovias mostradas no mapa. |
| 19 | Ao clicar em uma dessas porções deverá ser informado ao usuário a quantidade de pessoas que responderam ao app e a porcentagem de sintomáticos. |
| 24 | Deve existir um sistema de recompensa para outras universidades. |
| 30 | Deve ser possível reportar bugs, e problemas técnicos pertinente ao sistema. |  
<br/>

## Usabilidade
A interface deve ser amigável ao usuário proporcinando a ele uma fácil interação sem que haja dificuldades ao utilizar qualquer funcionalidade. Além disso, o usuário poderá enviar mensagens de erro para a equipe de desenvolvimento.

* A interface gráfica deve ser agradável, limpa e intuitiva.
* O sistema deverá possibilitar acesso fácil às diversas telas do aplicativo.
* O sistema deverá nomear as ruas, vias e rodovias mostradas no mapa de forma correta.
* Deverá existir um sistema de recompensa para outras universidades.
* Deve ser possível reportar bugs, e problemas técnicos pertinente ao sistema.
<br/>

## Confiabilidade
A aplicação deverá apresentar informações corretas e concretas sobre os dados obtidos através das participações dos usuários.

* O Mapa deverá informar informações corretas sobre as regiões e cidades contidas.
* O Mapa deverá mostrar a quantidade correta de pessoas doentes por região.
* O sistema deve garantir que o usuário informe seu estado de saúde somente uma vez ao dia.
* O sistema deve responder as ações do usuário com feedback.
* O sistema deve se recuperar de falhas, caso alguma ocorra.
<br/>

## Desempenho
O sistema deverá interagir da forma mais rápida possível com o usuário, evitando gargalos em sua interface.

* O sistema deverá informar rapidamente ao usuário a quantidade de pessoas que responderam ao app e a porcentagem de sintomáticos.
* As informações sobre os sintomáticos deverão ir aparecendo para o usuário conforme ele for navegando pelo mapa sem que haja demora.
* O sistema deve ter um curto tempo de resposta às ações do usuário, dentro de 400ms.
<br/>

## Suportabilidade
O aplicativo Guardiões da Saúde deverá ser disponibilizado para as plataformas IOS (versão 9.0 ou superior) e Android (versão 4.1 ou superior). Deverá também suportar grandes quantidades de acessos simultâneos.

* Disponível para as plataformas IOS e Android.
* Suportar vários acessos simultâneos.
<br/>

## Requisito Físico
* O sistema não poderá exceder os tamanhos de 40Mb para IOS e 20Mb para Android.
* O smartphone deverá ter conexão com a internet para que o aplicativo funcione corretamente.
<br/>

# Versionamento de edição

<table>
  <thead>
    <tr>
      <th>Data</th>
      <th>Autor</th>
      <th>Descrição</th>
      <th>Versão</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>06/10/2020</td>
      <td>Kalebe Lopes</td>
      <td>Criação do documento.</td>
      <td>0.1</td>
    </tr>
    <tr>
      <td>08/10/2020</td>
      <td>Kalebe Lopes</td>
      <td>Adição da especificação suplementar</td>
      <td>0.2</td>
    </tr>
    <tr>
      <td>25/11/2020</td>
      <td>Wagner Martins</td>
      <td>Correção conforme a verificação do artefato</td>
      <td>1.0</td>
    </tr>
  </tbody>
</table>

# Referências

Samily, Francisco. PHP SOFTWARE COMPANY. PHP, 2020. Disponível em: https://aprender3.unb.br/pluginfile.php/426762/mod_resource/content/1/Especificacao_Suplementar_Exemplo.pdf. Acesso em: 08 de Outubro de 2020.

EELES, Peter. Capturing Architectural Requirements. IBM, 2020. Disponível em: <https://www.ibm.com/developerworks/rational/library/4706.html>. Acesso em: 06 de Outubro de 2020.
