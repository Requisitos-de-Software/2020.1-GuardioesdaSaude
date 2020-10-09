# Diagrama de Casos de Uso

<p align='justify'>É um diagrama que mostra um sistema ou um aplicativo, as pessoas, organizações ou outros sistemas que interagem com ele, e um fluxo básico do que o sistema faz, sendo uma abordagem que não mostra muitos detalhes, útil para quando se quer mostrar as ideias de forma simples.</p>

<p align='justify'>É representado em notação UML (Unified Modeling Language) e focado em requisitos funcionais.</p>

## Diagrama de casos de uso - Guardiões da Saúde

![Casos de uso](https://user-images.githubusercontent.com/47457792/95368370-682b5700-08ac-11eb-9355-97a77c2f4182.png)

<p align='center'>Figura 01 - Diagrama de Casos de Uso</p>

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

**UC02 - Editar informações de perfis**

| **Descrição/Objetivo** | Editar informações de qualquer perfil atrelado a conta do usuário |
|------|-------|
| **Ator principal**  | Usuário logado no sistema |
| **Fluxo principal** | Usuário abre o aplicativo. <br>Usuário clica no menu esquerdo do aplicativo.<br>Usuário clica em Editar Perfis.<br>Usuário seleciona o perfil que deseja editar.<br>Usuário faz as modificações.<br>Usuário clica em salvar.<br>Sistema salva as novas informações do perfil |
| **Fluxo Alternativo 1** | Usuário abre o aplicativo.<br>Usuário clica no menu esquerdo do aplicativo.<br>Usuário clica em Editar Perfis.<br>Usuário seleciona o perfil que deseja editar.<br>Usuário faz as modificações.<br>Usuário deixa alguns campos sem preenchimento.<br>Usuário clica em salvar.<br>Aplicativo exibe tela de erro informando campos obrigatórios não preenchidos.<br>Aplicativo volta para a tela do formulário |
| **Fluxo de exceção** | Servidor está indisponível e não pode salvar perfil no sistema |

<br>

**UC03 - Adicionar membro da família**

| **Descrição/Objetivo** | Adicionar perfil de alguém próximo ao usuário principal |
|------|-------|
| **Ator principal**  | Usuário logado no sistema |
| **Fluxo principal** | Usuário abre o aplicativo. <br>Usuário clica na foto de perfil na home.<br>Usuário clica em adicionar perfil.<br>Usuário preenche o formulário e clica em Criar.<br>Sistema salva novo perfil. |
| **Fluxo Alternativo 1** | Usuário abre o aplicativo.<br>Usuário clica na foto de perfil na home.<br>Usuário clica em adicionar perfil.<br>Usuário preenche alguns campos do formulário.<br>Usuário clica em Cadastrar.<br>Aplicativo exibe tela de erro informando campos obrigatórios não preenchidos.<br>Aplicativo retorna a tela do formulário. |

<br>

## Histórico de Revisões

| Autor | Versão | Data(dd/mm/aaa) | Descrição
|------|-------|-------|-------
| Wagner Martins | 1.0 | 07/10/2020 | Adição de informações sobre casos de uso e do diagrama

## Referências

Material de apoio: Requisitos - Aula 11. Disponível em: <https://aprender3.unb.br/pluginfile.php/426751/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf>

LUCIDCHART PORTUGUÊS. **Tutorial de Caso de Uso UML**. 2019. (13m25s). Disponível em: <https://www.youtube.com/watch?v=ab6eDdwS3rA&feature=youtu.be>
