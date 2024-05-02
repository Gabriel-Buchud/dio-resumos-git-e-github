# DIO | Resumos Git & GitHub

A idéia deste repositório é armazenar informações sobre Git & GitHub, enquanto avanço meus estudos no curso sobre versionamento de código na plataforma da [Digital Innovation One](https://www.dio.me/).

## 📝 Docs utilizados

- [Documentação Git](https://git-scm.com/doc)
- [Documentação GitHub](https://docs.github.com/pt)
- [Documentação Markdown](https://www.markdownguide.org/basic-syntax/)

## 🤓 Aprendendo sobre versionamento de código

**1**. **O que é Versionamento de Código?**
: Versionamento de código é o processo de rastrear e gerenciar alterações no código-fonte de um projeto ao longo do tempo. Ele permite registrar cada modificação feita no código, facilitando a colaboração entre desenvolvedores, o controle de qualidade e a implantação de novas versões do software.

**2**. **Benefícios do Versionamento de Código**
: O versionamento de código oferece diversos benefícios, incluindo a capacidade de controlar e documentar mudanças, rastrear problemas e bugs, facilitar a colaboração entre equipes, permitir o retorno a versões anteriores do código e possibilitar a implantação automatizada do software.

**3**. **Ferramentas de Versionamento de Código**
: Existem várias ferramentas populares para versionamento de código, como Git, Mercurial e SVN. O Git é amplamente adotado devido à sua velocidade, flexibilidade e recursos avançados, como branches e merges eficientes.

**4**. **Fluxo de Trabalho com Git**
: No Git, os desenvolvedores geralmente seguem um fluxo de trabalho baseado em branches, onde cada funcionalidade ou correção de bug é desenvolvida em uma branch separada e, em seguida, integrada de volta à branch principal por meio de merges ou pull requests após revisão.

**5**. **Padrões de Versionamento Semântico**
: O versionamento semântico é uma abordagem para atribuir significado a versões de software com base em regras específicas. Geralmente segue o formato MAJOR.MINOR.PATCH, onde a versão MAJOR é incrementada para mudanças incompatíveis, MINOR para adições compatíveis e PATCH para correções de bugs compatíveis com versões anteriores. Isso facilita a compreensão das mudanças entre versões e ajuda na tomada de decisões de atualização.

## 🔍Funcionalidades do Git & GitHub

| Funcionalidades do Git     | Descrição                                                                                                                                                                                                                                      |
| -------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Controle de Versão         | Git permite rastrear e controlar as alterações feitas no código-fonte de um projeto ao longo do tempo, mantendo um histórico detalhado de cada modificação.                                                                                    |
| Branches                   | Branches no Git permitem que desenvolvedores trabalhem em paralelo em diferentes funcionalidades ou correções de bugs, isolando o trabalho em progresso do restante do código.                                                                 |
| Merges e Rebase            | Git oferece mecanismos para integrar alterações de diferentes branches, seja através de merges, que combinam históricos de alterações, ou rebase, que move as alterações de uma branch para outra.                                             |
| Stash                      | Stash é uma funcionalidade que permite aos desenvolvedores salvar temporariamente alterações não finalizadas, permitindo que eles alternem rapidamente entre tarefas sem comprometer o trabalho em andamento.                                  |
| Histórico Detalhado        | Git mantém um histórico detalhado de cada alteração, incluindo informações como autor, data e mensagem de commit, facilitando a compreensão das mudanças feitas ao longo do tempo.                                                             |
| Revert e Reset             | Git fornece maneiras de desfazer alterações indesejadas, seja através do comando `git revert`, que cria um novo commit que desfaz as alterações de um commit anterior, ou `git reset`, que permite redefinir o HEAD para um estado específico. |
| Submódulos e Subárvores    | Git oferece suporte a submódulos e subárvores, permitindo que os desenvolvedores incluam repositórios externos dentro de seus próprios projetos, facilitando a reutilização de código e o gerenciamento de dependências.                       |
| Ferramentas de Colaboração | Git oferece várias ferramentas e recursos para facilitar a colaboração entre desenvolvedores, como pull requests, issues, e integração com plataformas de hospedagem como GitHub e GitLab.                                                     |

| Funcionalidades do GitHub | Descrição                                                                                                                                                         |
| ------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Repositórios              | Os repositórios no GitHub são espaços onde você pode armazenar, organizar e compartilhar seus projetos de software.                                               |
| Issues                    | As issues são usadas para rastrear tarefas, bugs ou solicitações de funcionalidades em um repositório, facilitando a colaboração e o acompanhamento do progresso. |
| Pull Requests             | Pull Requests (PRs) são propostas de alterações enviadas para um repositório, permitindo revisões e integração de contribuições, facilitando a colaboração.       |
| README                    | O README é um arquivo Markdown exibido na página inicial de um repositório, usado para fornecer informações sobre o projeto e como contribuir para ele.           |
| GitHub Pages              | GitHub Pages é um serviço que permite hospedar sites estáticos diretamente a partir de repositórios do GitHub, facilitando a criação de sites e documentação.     |

## 💻 Comandos básicos no Git

| Comando                    | Descrição                                                                                                                              |
| -------------------------- | -------------------------------------------------------------------------------------------------------------------------------------- |
| `git clone <URL>`          | Clona um repositório Git existente, criando uma cópia local do projeto em seu ambiente de desenvolvimento.                             |
| `git init`                 | Inicializa um novo repositório Git em um diretório local, permitindo que você comece a rastrear alterações.                            |
| `git add <arquivo>`        | Adiciona alterações de um arquivo específico ao área de preparação (staging), preparando-o para commit.                                |
| `git commit -m "mensagem"` | Registra as alterações no repositório, incluindo uma mensagem que descreve as mudanças feitas no código.                               |
| `git status`               | Exibe o estado atual do repositório, mostrando quais arquivos foram modificados, adicionados ou removidos.                             |
| `git push`                 | Envia os commits locais para um repositório remoto, atualizando a versão remota do projeto com as alterações feitas.                   |
| `git pull`                 | Atualiza o repositório local com as alterações do repositório remoto, trazendo as alterações para o ambiente de desenvolvimento local. |
| `git fetch`                | Recupera todas as alterações do repositório remoto para o repositório local, sem mesclá-las automaticamente com o código local.        |
| `git branch`               | Lista todas as branches presentes no repositório, mostrando a branch atual e destacando a branch ativa.                                |
| `git checkout <branch>`    | Muda para a branch especificada, permitindo que você trabalhe em diferentes funcionalidades ou correções de bugs.                      |
| `git merge <branch>`       | Combina as alterações de uma branch específica com a branch atual, integrando as mudanças de ambas as branches.                        |
| `git log`                  | Mostra um registro detalhado de todos os commits feitos no repositório, exibindo informações como autor, data e mensagem de commit.    |
