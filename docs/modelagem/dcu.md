# Diagrama de Casos de Uso

<p align='justify'>É um diagrama que mostra um sistema ou um aplicativo, as pessoas, organizações ou outros sistemas que interagem com ele, e um fluxo básico do que o sistema faz, sendo uma abordagem que não mostra muitos detalhes, útil para quando se quer mostrar as ideias de forma simples.</p>

<p align='justify'>É representado em notação UML (Unified Modeling Language) e focado em requisitos funcionais.</p>

## Diagrama de casos de uso - Guardiões da Saúde

![Casos de uso](https://user-images.githubusercontent.com/47457792/95368370-682b5700-08ac-11eb-9355-97a77c2f4182.png)

<p align='center'>Figura 01 - Diagrama de Casos de Uso</p>

<br>
<br>

## Especificação de casos de uso - Guardiões da Saúde

**UC01 - Cadastrar**

| **Descrição/Objetivo** | Criar uma conta no aplicativo Guardiões da saúde |
|------|-------|
| **Ator principal**  | Usuário que ainda não tem cadastro |
| **Fluxo principal** | Usuário abre o aplicativo. <br>Usuário clica em cadastrar-se na tela de início <br>Usuário lê os termos e políticas e clica em ok <br>Usuário preenche o formulário de cadastro e clica em Cadastrar <br>Sistema checa se email e senha são válidos <br>Usuário é cadastrado|
| **Fluxo Alternativo 1** | Usuário abre o aplicativo <br>Usuário clica em cadastrar-se na tela de início <br>Usuário lê os termos e políticas e clica em cancelar <br>Aplicativo volta para a tela de início|
| **Fluxo Alternativo 2** | Usuário abre o aplicativo <br>Usuário clica em cadastrar-se na tela de início <br>Usuário lê os termos e políticas e clica em ok <br>Usuário preenche alguns campos do formulário <br>Usuário clica em Cadastrar <br>Sistema checa os campos <br>Aplicativo exibe tela de erro informando campos obrigatórios não preenchidos <br>Aplicativo volta para a tela do formulário <br>|
| **Fluxo de exceção** | Servidor está indisponível e não pode cadastrar usuário no sistema |

<br>
<br>

**UC02 - Editar informações de perfis**

| **Descrição/Objetivo** | Editar informações de qualquer perfil atrelado a conta do usuário |
|------|-------|
| **Ator principal**  | Usuário logado no sistema |
| **Fluxo principal** | Usuário abre o aplicativo. <br>Usuário clica no menu esquerdo do aplicativo.<br>Usuário clica em Editar Perfis.<br>Usuário seleciona o perfil que deseja editar.<br>Usuário faz as modificações.<br>Usuário clica em salvar.<br>Sistema salva as novas informações do perfil |
| **Fluxo Alternativo 1** | Usuário abre o aplicativo.<br>Usuário clica no menu esquerdo do aplicativo.<br>Usuário clica em Editar Perfis.<br>Usuário seleciona o perfil que deseja editar.<br>Usuário faz as modificações.<br>Usuário deixa alguns campos sem preenchimento.<br>Usuário clica em salvar.<br>Aplicativo exibe tela de erro informando campos obrigatórios não preenchidos.<br>Aplicativo volta para a tela do formulário |
| **Fluxo de exceção** | Servidor está indisponível e não pode salvar perfil no sistema |

<br>
<br>

**UC03 - Adicionar membro da família**

| **Descrição/Objetivo** | Adicionar perfil de alguém próximo ao usuário principal |
|------|-------|
| **Ator principal**  | Usuário logado no sistema |
| **Fluxo principal** | Usuário abre o aplicativo. <br>Usuário clica na foto de perfil na home.<br>Usuário clica em adicionar perfil.<br>Usuário preenche o formulário e clica em Criar.<br>Sistema salva novo perfil. |
| **Fluxo Alternativo 1** | Usuário abre o aplicativo.<br>Usuário clica na foto de perfil na home.<br>Usuário clica em adicionar perfil.<br>Usuário preenche alguns campos do formulário.<br>Usuário clica em Cadastrar.<br>Aplicativo exibe tela de erro informando campos obrigatórios não preenchidos.<br>Aplicativo retorna a tela do formulário. |
| **Fluxo de exceção** | Servidor está indisponível. |

<br>
<br>

**UC04 - Logar**

| **Descrição/Objetivo** | Realizar login no Guardiões da Saúde |
|------|-------|
| **Ator principal**  | Usuário não logado, mas cadastrado |
| **Fluxo principal** | Usuário abre o aplicativo.<br>Usuário clica em Entrar.<br>Usuário preenche email e senha.<br>Sistema verifica os dados.<br>Usuário entra em sua conta.|
| **Fluxo Alternativo 1** | Usuário abre o aplicativo.<br>Usuário clica em Entrar.<br>Usuário preenche email e senha.<br>Sistema verifica os dados.<br>Aplicativo mostra tela de erro.<br>Aplicativo retorna para a tela de login.|
| **Fluxo de exceção** | Servidor está indisponível |

<br>
<br>

**UC03 - Adicionar membro da família**

| **Descrição/Objetivo** | Adicionar perfil de alguém próximo ao usuário principal |
|------|-------|
| **Ator principal**  | Usuário logado no sistema |
| **Fluxo principal** | Usuário abre o aplicativo. <br>Usuário clica na foto de perfil na home.<br>Usuário clica em adicionar perfil.<br>Usuário preenche o formulário e clica em Criar.<br>Sistema salva novo perfil. |
| **Fluxo Alternativo 1** | Usuário abre o aplicativo.<br>Usuário clica na foto de perfil na home.<br>Usuário clica em adicionar perfil.<br>Usuário preenche alguns campos do formulário.<br>Usuário clica em Cadastrar.<br>Aplicativo exibe tela de erro informando campos obrigatórios não preenchidos.<br>Aplicativo retorna a tela do formulário. |
| **Fluxo de exceção** | Servidor está indisponível |

<br>
<br>

**UC05 - Enviar status**

| **Descrição/Objetivo** | Informar a o estado de saúde |
|------|-------|
| **Ator principal**  | Usuário logado no sistema |
| **Fluxo principal** | Usuário abre o aplicativo.<br>Usuário faz login com email e senha.<br>Usuário clica no botão home.<br>Usuário informa estado de saúde. |
| **Fluxo Alternativo 1** | Usuário abre o aplicativo.<br>Usuário faz login com email e senha.<br>Usuário clica no botão Home.<br>Usuário informa má estado de saúde.<br>Usuário informa seus sintomas.<br>Sistema verifica se os sintomas correspondem ao covid-19.<br>Sistema volta para a tela inicial caso os sintomas não correspondam ao covid-19. |
| **Fluxo Alternativo 2** | Usuário abre o aplicativo.<br>Usuário faz login com email e senha.<br>Usuário clica no botão Home.<br>Usuário informa má estado de saúde.<br>Usuário informa seus sintomas.<br>Sistema verifica se os sintomas correspondem ao covid-19.<br>Sistema exibe mensagem informando que os sintomas correspondem ao covid-19. |
| **Fluxo de exceção 1** | Mensagem de erro caso o usuário já tenha informado seu estado de saúde nesse dia. |
| **Fluxo de exceção 2** | Servidor está indisponível. |

<br>
<br>

**UC06 - Acessar diário**

| **Descrição/Objetivo** | Obter informações sobre os datas e as estatísticas dos relatos. |
|------|-------|
| **Ator principal**  | Usuário logado no sistema |
| **Fluxo principal** | Usuário abre o aplicativo.<br>Usuário faz login com email e senha.<br>Usuário clica no botão Diário. |
| **Fluxo de exceção** | Servidor está indisponível. |

<br>
<br>

**UC07 - Visualizar mapa**

| **Descrição/Objetivo** | Visualizar o mapa e os infectados da região  |
|------|-------|
| **Ator principal**  | Usuário logado no sistema |
| **Fluxo principal** | Usuário abre o aplicativo.<br>Usuário faz login com email e senha.<br>Usuário clica no botão Mapa.<br>Sistema acessa o mapa com base na localização do usuário.<br>Usuário seleciona a região que deseja visualizar as informações. |
| **Fluxo de exceção 1** | Aplicativo sem acesso a localização. |
| **Fluxo de exceção 2** | Servidor está indisponível. |

<br>
<br>

**UC08 - Visualizar dicas**

| **Descrição/Objetivo** | Visualizar as dicas disponíveis para o usuário manter sua saúde em dia. |
|------|-------|
| **Ator principal**  | Usuário logado no sistema |
| **Fluxo principal** | Usuário abre o aplicativo.<br>Usuário faz login com email e senha.<br>Usuário clica no botão Dicas.<br>Sistema exibe os tópicos das dicas de saúde.<br>Usuário seleciona o tópico que deseja. |
| **Fluxo Alternativo 1** | Usuário abre o aplicativo.<br>Usuário faz login com email e senha.<br>Usuário clica no botão Dicas.<br>Sistema exibe os tópicos das dicas de saúde.<br>Usuário seleciona o tópico que deseja.<br>Usuário clica no botão Saiba Mais para ser redirecionado para o site oficial da matéria. |
| **Fluxo de exceção 1** | Site oficial da matéria fora do ar. |
| **Fluxo de exceção 2** | Servidor está indisponível. |

<br>
<br>

**UC09 - Visualizar notícias**

| **Descrição/Objetivo** | Visualizar as últimas notícias do feed do Guardiões da Saúde no Twitter. |
|------|-------|
| **Ator principal**  | Usuário logado no sistema |
| **Ator secundário**  | Twitter |
| **Fluxo principal** | Usuário abre o aplicativo.<br>Usuário faz login com email e senha.<br>Usuário clica no botão Notícias.<br>Sistema exibe as últimas notícias do feed no Twitter. |
| **Fluxo Alternativo 1** | Usuário abre o aplicativo.<br>Usuário faz login com email e senha.<br>Usuário clica no botão Notícias.<br>Sistema exibe as últimas notícias do feed no Twitter.<br>Usuário clica na notícia desejada para ser redirecionado para o Twitter. |
| **Fluxo de exceção 1** | Servidor está indisponível. |

<br>
<br>

## Histórico de Revisões

| Autor | Versão | Data(dd/mm/aaa) | Descrição
|------|-------|-------|-------
| Wagner Martins | 1.0 | 07/10/2020 | Adição de informações sobre casos de uso e do diagrama
| Kalebe Lopes   | 2.0 | 08/10/2020 | Adição das especificações de casos de uso

## Referências

Material de apoio: Requisitos - Aula 11. Disponível em: <https://aprender3.unb.br/pluginfile.php/426751/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf>

LUCIDCHART PORTUGUÊS. **Tutorial de Caso de Uso UML**. 2019. (13m25s). Disponível em: <https://www.youtube.com/watch?v=ab6eDdwS3rA&feature=youtu.be>
