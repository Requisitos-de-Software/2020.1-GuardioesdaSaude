# Backlog

<p align="justify">
Backlog é uma lista com prioridades dos requisitos ou funcionalidades do projeto que fornecem valor comercial ao cliente. Geralmente utilizado na técnica de desenvolvimento ágil, SCRUM. Os itens podem ser adicionados a esse registro em qualquer momento. Cabe ao gerente de produto avaliar o registro e atualizar as prioridades conforme requisitado.
</p>

O Backlog do produto deve ser:

* Detalhado o suficiente para que os desenvolvedores consigam entregar as funcionalidades ou histórias de usuário descritas.
* Estimável de forma a ser possível dizer quanto tempo levará para implementar a funcionalidade.
* Emergente de forma que possa ser continuamente atualizado.
* Priorizado de forma a trazer maior valor para o cliente.

<p align="justify">
Backlogs são focados em histórias de usuário, e contém sua descrição, identificação e priorização.
</p>

## Histórias de Usuário (User Stories)

<p align="justify">
Histórias de Usuário, como o próprio nome diz, são histórias focadas no usuário que descrevem de forma simples funcionalidades do produto de software. Por serem focadas no usuário, apresentam uma abordagem do que deve ser feito e não como. Devem ser detalhadas o suficiente para se poder derivar as tarefas necessárias para a implementação, e podem ter critérios de aceitação.
</p>

São escritas no formato:

**_Eu, como (quem?) quero (o quê?) para (por quê?)._**

## Backlog - Guardiões da Saúde

<style>
    #celula {
        vertical-align: middle;
        text-align: center;
        border: 0.5px solid rgba(0,0,0,0.2);
    }
</style>

<table>
    <thead>
        <tr>
            <th>Épico</th>
            <th>Feature</th>
            <th>ID</th>
            <th>História de Usuário</th>
            <th>Prioridade</th>
        </tr>
    </thead>
    <tbody >
        <tr>
            <td id="celula" rowspan="4">E01<br>Acesso</td>
            <td id="celula">F01<br>Cadastro</td>
            <td id="celula">US01</td>
            <td id="celula">Eu, como usuário quero cadastrar um email e senha para acessar o aplicativo.</td>
            <td id="celula">Alta</td>
        </tr>
        <tr>
            <td id="celula" rowspan="2">F02<br>Login</td>
            <td id="celula">US02</td>
            <td id="celula">Eu, como usuário quero logar usando o email e senha para                   acessar o aplicativo.</td>
            <td id="celula">Alta</td>
        </tr>
        <tr>
            <td id="celula">US03</td>
            <td id="celula">Eu, como usuário quero poder recuperar senha caso eu a esqueça             para acessar o aplicativo.</td>
            <td id="celula">Alta</td>
        </tr>
        <tr>
            <td id="celula" rowspan="1">F03<br>Logout</td>
            <td id="celula">US04</td>
            <td id="celula">Eu, como usuário quero poder fazer logout para sair da                     conta</td>
            <td id="celula">Alta</td>
        </tr>
        <tr>
              <td id="celula"rowspan="11">E02<br>Perfil</td>
              <td id="celula"rowspan="11">F04<br>Edição de perfil</td>
              <td id="celula">US05</td>
              <td id="celula">Eu, como usuário quero poder alterar meu nome no perfil para               mantê-lo atualizado ou corrigí-lo em caso de erro no cadastro.</td>
              <td id="celula">Alta</td>
          </tr>
          <tr>
              <td id="celula">US06</td>
              <td id="celula">Eu, como usuário quero poder alterar meu gênero para                       manter as informações atualizadas.</td>
              <td id="celula">Média</td>
          </tr>
          <tr>
              <td id="celula">US07</td>
              <td id="celula">Eu, como usuário quero poder alterar minha cor para                       adicionar a informação ou corrigir possível erro no cadastro.</td>
              <td id="celula">Média</td>
          </tr>
          <tr>
              <td id="celula">US08</td>
              <td id="celula">Eu, como usuário quero poder alterar minha data de                         nascimento para adicionar a informação ou corrigir possível erro no cadastro.</td>
              <td id="celula">Média</td>
          </tr>
          <tr>
              <td id="celula">US09</td>
              <td id="celula">Eu, como usuário poder alterar meu país de origem para                     adicionar a informação ou corrigir possível erro no cadastro.</td>
              <td id="celula">Média</td>
          </tr>
          <tr>
              <td id="celula">US10</td>
              <td id="celula">Eu, como usuário quero poder informar se sou integrante de                 alguma instituição de ensino para adicionar a informação ou corrigir possível erro no cadastro.</td>
              <td id="celula">Média</td>
          </tr>
          <tr>
              <td id="celula">US11</td>
              <td id="celula">Eu, como usuário quero poder informar/alterar o país da                   minha universidade para atualizar informação sobre meu local de estudo.</td>
              <td id="celula">Média</td>
          </tr>
          <tr>
              <td id="celula">US12</td>
              <td id="celula">Eu, como usuário quero poder poder informar/alterar o estado               da minha universidade para atualizar informação sobre meu local de estudo.</td>
              <td id="celula">Média</td>
          </tr>
         <tr>
              <td id="celula">US13</td>
              <td id="celula">Eu, como usuário quero poder informar/alterar a                           cidade/município da minha universidade para atualizar informação sobre meu local de estudo.</td>
              <td id="celula">Média</td>
         </tr>
         <tr>
              <td id="celula">US14</td>
              <td id="celula">Eu, como usuário quero poder informar/alterar o nome da                   minha universidade para atualizar informação sobre minha instituição de ensino.</td>
              <td id="celula">Alta</td>
         </tr>
         <tr>
              <td id="celula">US15</td>
              <td id="celula">Eu, como usuário quero poder informar/alterar minha                       matrícula para atualizar informação sobre minha instituição de ensino.</td>
              <td id="celula">Alta</td>
        </tr>
        <tr>
              <td id="celula"rowspan="4">E03<br>Informe</td>
              <td id="celula"rowspan="4">F05<br>Relato</td>
              <td id="celula">US16</td>
              <td id="celula">Eu, como usuário quero poder relatar que estou bem para                   salvar no histórico e ajudar a comunidade.</td>
              <td id="celula">Alta</td>
          </tr>
          <tr>
              <td id="celula">US17</td>
              <td id="celula">Eu, como usuário quero poder relatar que estou mal para                   salvar no histórico e alertar a comunidade.</td>
              <td id="celula">Alta</td>
          </tr>
          <tr>
              <td id="celula">US18</td>
              <td id="celula">Eu, como usuário quero poder indicar meus sintomas caso                   esteja mal para saber se possívelmente estou com covid-19.</td>
              <td id="celula">Alta</td>
          </tr>
          <tr>
              <td id="celula">US19</td>
              <td id="celula">Eu, como usuário quero receber alerta do meu status de saúde               nos últimos 7 dias para acompanhar a evolução dos sintomas.</td>
              <td id="celula">Alta</td>
          </tr>
        <tr>
            <td id="celula"rowspan="5">E04<br>Mapa</td>
            <td id="celula"rowspan="5">F06<br>Marcações</td>
            <td id="celula">US20</td>
            <td id="celula">Eu, como usuário quero poder ter marcações visuais na cor verde             para saber que a região está segura.</td>
            <td id="celula">Alta</td>
        </tr>
        <tr>
            <td id="celula">US21</td>
            <td id="celula">Eu, como usuário quero poder ter marcações visuais na cor                   amarela para saber que a região tem risco de contágio.</td>
            <td id="celula">Alta</td>
        </tr>
        <tr>
            <td id="celula">US22</td>
            <td id="celula">Eu, como usuário quero poder ter marcações visuais na cor                   vermelha para saber que a região tem alto risco de contágio.</td>
            <td id="celula">Alta</td>
        </tr>
        <tr>
            <td id="celula">US23</td>
            <td id="celula">Eu, como usuário quero poder olhar quantas pessoas estão com               sintomas de covid-19 através das marcações para saber qual o risco de contágio.</td>
            <td id="celula">Média</td>
        </tr>
        <tr>
            <td id="celula">US24</td>
            <td id="celula">Eu, como usuário quero poder olhar qual a porcentagem de                   sintomáticos através das marcações para saber qual o risco de contágio .</td>
            <td id="celula">Média</td>
        </tr>
        <tr>
            <td id="celula"rowspan="6">E05<br>Diário</td>
            <td id="celula"rowspan="3">F07<br>Calendário</td>
            <td id="celula">US25</td>
            <td id="celula">Eu, como usuário quero poder olhar os dias que foram relatados             em forma de calendário para saber se estou relatando diáriamente.</td>
            <td id="celula">Alta</td>
        </tr>
        <tr>
            <td id="celula">US26</td>
            <td id="celula">Eu, como usuário quero poder olhar os dias que foram deixados               de serem relatados para saber se estou relatando diáriamente.</td>
            <td id="celula">Alta</td>
        </tr>
        <tr>
            <td id="celula">US27</td>
            <td id="celula">Eu, como usuário quero ter marcações verdes no calendário para             cada dia que relatei estar bem para ter um acompanhamento periodico sobre a minha saúde.</td>
            <td id="celula">Alta</td>
        </tr>
        <tr>
            <td id="celula"rowspan="1">F08<br>Estatísticas</td>
            <td id="celula">US28</td>
            <td id="celula">Eu, como usuário quero ver as estatísticas dos meus relatos em             forma de gráfico para ter um acompanhamento sobre minha saúde.</td>
            <td id="celula">Alta</td>
        </tr>
        <tr>
            <td id="celula"rowspan="2">F09<br>Registro Total dos Relatos</td>
            <td id="celula">US29</td>
            <td id="celula">Eu, como usuário quero saber o total de dias que informei estar             bem para ter um acompanhamento sobre minha saúde.</td>
            <td id="celula">Alta</td>
        </tr>
        <tr>
            <td id="celula">US30</td>
            <td id="celula">Eu, como usuário quero saber o total de dias que informei estar             mal para ter um acompanhamento sobre minha saúde.</td>
            <td id="celula">Alta</td>
        </tr>
        <tr>
            <td id="celula"rowspan="2">E06<br>Informações</td>
            <td id="celula"rowspan="1">F10<br>Notícias</td>
            <td id="celula">US31</td>
            <td id="celula">Eu, como usuário quero ter acesso as últimas notícias dos Guardiões da Saúde para me menter atualizado.</td>
            <td id="celula">Média</td>
        </tr>
        <tr>
            <td id="celula"rowspan="2">F11<br>Dicas</td>
            <td id="celula">US32</td>
            <td id="celula">Eu, como usuário quero receber dicas de prevenção para                manter minha saúde em dia.</td>
            <td id="celula">Média</td>
        </tr>
    </tbody>
</table>



## Histórico de Revisões

Autor | Versão | Data(dd/mm/aaa) | Descrição
-|-|-|-
Wagner Martins | 1.0 | 26/10/2020 | Adição de informações sobre o Backlog e Histórias de Usuário
Kalebe Lopes   | 2.0 | 26/10/2020 | Adição da tabela, backlog e user histories
Wagner Martins | 2.1 | 22/11/2020 | Correções a partir da [verificação](../verificacao-e-validacao/lexico): Adição de identificadores nos épicos e features

## Referências

* LuizTools. **Product Backlog - Introdução**. Disponível em: <https://www.youtube.com/watch?v=z4ubaBwjCsU&feature=youtu.be>

* Slides da aula 15
