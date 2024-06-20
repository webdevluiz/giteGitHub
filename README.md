# GitHub&Git
| Reciclagem dos conhecimentos e das funcionalidades de uso so Git e do GitHub. |
# Git -  sistema de controle de versão
| **Git**: Pode ser resumido como um sistema de controle de versões local para  rastrear códigos criados e modificados, seus savepoints de alteração são marcados por *COMMITS*.

| **Commits no Git** :São publicações de registros das alterações feitas no código. Eles incluem uma mensagem que descreve as alterações, o autor da alteração e um carimbo de data/hora. Os commits são usados para rastrear o histórico do projeto e colaborar com outras pessoas.

| **.git**: A pasta .git é um diretório oculto que contém todas as informações sobre o repositório Git, incluindo o histórico de commits, branches e o índice de arquivos rastreados. <strong>É essencial para o funcionamento do Git e não deve ser excluído ou modificado manualmente.</strong>

> Comandos CMD para git (use a interface gráfica)
> - ls : lista os elementos visíveis no repositório.
> - mk__ name : Cria um elemento (mkdir diretório, mk).
> - mv name new_Name :Altera o nome do arquivo.
> - cd name :Transita para a pasta name (change directory).
> - git init :Inicializa o git.
> - ls -a :Exibe pastas ocultas.
> - clear :Limpa o prompt.
> - cd .. :Retorna a pasta que possui seu diretório atual a qual você está situacionado.
> - git config --global user.name "nome Usuário" :Aloca o nome que ficará registrado no git.
> - git config --global user.email "usuário@gmail.com" :Aloca o email que receberá o commit.
> - git config --global --list :Mostra as configurações globais salvas (core.editor, credential.https, user.name e user.email).
> - git config --list :Mostra TODAS as configs do sistema git.

- | **Branch no Git**: São ramificações do código principal, como se fossem pastas de cópia assincronas do código. Elas permitem que você trabalhe em diferentes versões do código simultaneamente, sem afetar o código principal. Isso é útil para recursos ou correções de bugs que ainda não estão prontos para serem mesclados com o código principal.

> - É possível realizar um MERGE na branch com a main, para verificar as alterações e diferenças entre os codigos, tendo sido resolvidas todos o conflitos, a branch integra a main, deixando o histórico de alterações versionado.
>
> - É possível utilizar o REBASE, que atualiza o código base utilizado pela branch para o atual, tendo resolvido todos os conflitos, a branch deixa de existir no histórico e integra a main, tornando o versionamento mais limpo.

- | **Tags** :São rótulos, usadas pra marcar pontos específicos (commit) no histórico do seu código, como atualizações e novas features, representando uma mudança significativa ou uma versão, direferentemente das branchs, as tags são fixas.

> - leves :Geralmente um commit sem informações específicas.
> - Anotada :Detalhada com datas, assinaturas e normalmente representam lançamentos.
# Tags & Branchs

**Tags** são marcadores imutáveis que identificam um commit específico, enquanto **branches** são ponteiros mutáveis que apontam para o commit mais recente.

* **Tags:**
    * Marcam um estado específico do projeto.
    * São imutáveis, ou seja, não podem ser movidas ou alteradas.
    * São usadas para identificar versões, marcos ou pontos de referência.

* **Branches:**
    * Representam linhas de desenvolvimento paralelas.
    * São mutáveis, ou seja, podem ser movidos e alterados.
    * São usados para trabalhar em diferentes recursos ou correções de bugs sem afetar o branch principal.