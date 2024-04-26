# Guia de Contribuição para o Repositório CTF Brasil 2024

Obrigado por considerar contribuir para o CTF Brasil 2024! Este guia foi criado para ajudá-lo a entender como você pode contribuir com este repositório e ajudar a comunidade CTF crescer cada vez mais!

## Antes de Começar
Antes de começar a contribuir, é importante entender a estrutura e o propósito do repositório CTF Brasil 2024. Dê uma olhada nos arquivos de documentação e nas informações sobre as competições já adicionadas. Isso ajudará você a ter uma ideia do que já foi feito e do que ainda precisa ser incluído.

## Como Contribuir?

> [!NOTE]
> Para submeter alterações no repositório será necessário criar commits e pull requests. Se é sua primeira contribuição com um repositório open source, [clique aqui](#primeira-contribuição).

### 1. Encontre Competições para Adicionar
Pesquise por competições de CTF que sejam abertas a participantes brasileiros e as liste em [issues](https://github.com/jojesd/CTF-Brasil-2024/issues). Podem ser inclusas competições locais, nacionais ou internacionais, tanto on-line quanto presencial, que permitam a participação de equipes ou indivíduos do Brasil. Verifique se essas competições ainda não foram listadas no repositório.

Desta forma, criar uma melhor distribuição do trabalho será mais fácil. Além de facilitar a discussão sobre as competições.

### 2. Adicione Novas Competições,
Depois de identificar competições que ainda não foram documentadas no repositório, é hora de adicioná-las. Escolha uma das [issues](https://github.com/jojesd/CTF-Brasil-2024/issues) existentes para contribuir e, caso não exista, crie um arquivo [markdown](https://www.markdownguide.org/basic-syntax/). Verifique os comentários para garantir que não há ninguém trabalhando na issue para que dois contribuidores não façam o mesmo trabalho. E, caso esteja livre, avise que você trabalhará nessa issue.

Certifique-se de fornecer informações precisas e detalhadas sobre cada competição, incluindo nome, organizador, datas relevantes, formato da competição, requisitos de participação e quaisquer outros links ou recursos adicionais que possam ser úteis para os participantes.

Após concluir, submeta suas alterações no repositório.

### 3. Atualize Informações Existentes
Se você encontrar informações ou documentos desatualizadas ou imprecisas já listadas no repositório, sinta-se à vontade para atualizá-las. Isso pode incluir correções de datas, links quebrados ou qualquer outra informação relevante. Não se esqueça de atualizar o histórico de versão antes do commit.

### 4. Colabore e Comente
Ao verificar [issues](https://github.com/jojesd/CTF-Brasil-2024/issues) e [pull requests](https://github.com/jojesd/CTF-Brasil-2024/pulls) de outros contribuidores, forneça feedback construtivo e ajude a garantir a qualidade e a precisão das informações no repositório. Comentários úteis podem ajudar a melhorar o conteúdo e promover uma comunidade colaborativa.

## Outras formas de contribuição
O CTF Brasil 2024 está em constante evolução. Não se prenda apenas a este guia. Se você enxerga uma forma de melhorar o repositório, seja com documentação, conteúdos, estrutura ou até mesmo código, crie uma issue para incentivar o debate sobre.

Contribuições adicionais são sempre bem-vindas e podem ajudar a tornar o repositório mais eficiente e útil para a comunidade CTF brasileira.

## Primeira Contribuição

### Criando uma issue
Uma issue no contexto do GitHub é uma forma de acompanhar, discutir e resolver problemas, ideias de novos recursos ou qualquer outra tarefa relacionada a um projeto. Ela é essencialmente um registro público de uma discussão específica ou de uma tarefa a ser realizada.

1. Faça login na sua conta do GitHub, se ainda não estiver conectado;
2. Acesse o [repositório](https://github.com/jojesd/CTF-Brasil-2024) no GitHub;
3. Clique na aba "Issues". Ela está localizada perto do topo da página, ao lado de "Pull requests" e "Projects".
4. Clique no botão verde "New issue".
5. Descreva a issue fornecendo título e um resumo conciso e descritivo sobre a sua solicitação. Tente ser claro para que outros contribuintes possam compreender;
6. Por fim, clique no botão verde "Submit new issue".

> [!IMPORTANT]
> Não se esqueça de checar se já não há uma issue criada sobre a sua solicitação para que não haja duplicações.

### Alterações no repositório

> [!IMPORTANT]
> Para realizar alterações no repositório será necessário ter o [Git]() instalado na sua máquina.

1. Faça login na sua conta do GitHub, se ainda não estiver conectado;
2. Acesse o [repositório](https://github.com/jojesd/CTF-Brasil-2024) no GitHub;
3. Faça um fork deste repositório para sua própria conta GitHub clicando no botão "Fork" no canto superior direito da página;
4. Abra o terminal no local onde deseja guardar os arquivos do projeto e clone seu fork para a sua máquina local usando o comando:
    ```
    git clone https://github.com/seu-usuario/CTF-Brasil-2024.git
    ```
    > [!IMPORTANT]
    > Não se esqueça de trocar "seu-usuario" pelo seu username no github.
5. Crie uma nova branch usando o comando:
    ```
    git checkout -b minha-contribuicao
    ```
6. Faça as alterações desejadas nos arquivos do repositório;
7. Commit suas alterações usando os comandos:
    ```
    git add .
    git commit -m "Adicionando [descrição da sua contribuição]"
    ```
    > [!TIP]
    > É possível visualizar as modificações a serem comittadas utilizando ```git status```.
8. Envie suas alterações para seu fork do repositório
    ```
    git push origin minha-contribuicao
    ```
9. Crie um Pull Request (PR)
    * Navegue até a página do seu fork no GitHub e clique no botão "Pull Request";
    * Descreva suas alterações de forma clara e concisa. Coloque também os critérios de aceitação que foram decididos na issue;
    * Após enviar o PR, os mantenedores do projeto revisarão suas alterações e fornecerão feedback, se necessário.
