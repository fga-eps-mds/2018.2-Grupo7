# PDF2CASH
---

O projeto PDF2CASH tem como objetivo gerar um aplicativo capaz de realizar análises por meio do tratamento de dados extraídos de notas fiscais eletrônicas.

## Informações gerais
---

O presente repositório é de uso da equipe PDF2CASH para fins gerênciais, tais como comunicação técnica,publicação de artefatos e definições metodólogicas. Para aqueles interessados em contribuir com o projeto, favor acesse o nosso [CONTRIBUTING.md](CONTRIBUTING.md).

## Repositórios _source_
---

Os repositórios _source_ estão disponíveis em [PDF2CASH](https://github.com/PDF2CASH).

### Equipe de Desenvolvimento

Membros da equipe que tem a responsabilidade de documentar parte do software, implementar e testá-lo e seguir a documentação relacionada às metodologias definidas.

| Nome | E-mail | Github |
| ---- | ------ |:------:|
| Brian Lui | brianlui2387@gmail.com | @Brian2397 |
| Julio Cesar Litwin | j.litwin@live.com | @jclitwin |
| Lucas Gomes Silva | lucas.gomesgs0@gmail.com | @lucasgomesgs0 |
| Luis Claudio Telles Lima | lclaudio.tl@gmail.com | @LuisCL94 |
| Rafael Santos Teodosio | rafael.s.t@hotmail.com | @rafaelteodosio |
| Wictor Bastos Girardi | wictor.girardi@gmail.com | @Wictorgirardi |


## Licensa
---

O projeto PDF2CASH é licenciado sobre a licença [MIT](LICENSE.md).

# Contribuindo com o PDF2CA$H.
***
Agredecemos sua vontade em contribuir com nosso projeto. A seguir encontram-se algumas diretrizes para aqueles que desejam realizar contribuições junto ao PDF2CA$H.

## Código de conduta

Ajude-nos a manter o bom convivio de nossa comunidade ao ler e seguir o nosso [código de conduta](/CODE_OF_CONDUCT.md).

## Como contribuir
***
### Reportando _bugs_
Caso tenha descoberto um _bug_ e deseja fazer um _report_ do mesmo por favor submita uma _issue_ seguindo este [template](ISSUE_TEMPLATE/bug_report.md).
### Sugerindo melhorias
Caso tenha sugestões de melhorias ou deseja fazer um pedido de uma nova _feature_ por favor submita uma _issue_ seguindo este [template](ISSUE_TEMPLATE/feature_request.md).
### _Pull Requests_
  * Preencha este [template](/PULL_REQUEST_TEMPLATE.md).
  * Siga o nosso [guia de estilo]().

## Guia de estilo
TODO / TBD
### Mensagens do git
  * Sempre use o infinitivo.
  * Usar o inglês.

  Certo:
  > Add new filter.

  Errado:
  > Adding new feature.

  * <a name="line-rule"></a>A primeira linha da mensagem deve ter no máximo 72 caracteres.

  * Use a primeira linha para fazer uma descrição sucinta da mudança proposta do commit. Use as linhas restantes para fazer uma descrição mais detalhas se for preciso.

  * Caso a mudança proposta no commit estiver relacionada à alguma issue favor  incluir uma indicação do mesmo da seguinte forma:
  > refs #<ISSUE_NUMBER>
  > refs #<ISSUE_NUMBER>, #<ISSUE_NUMBER>, ...

  A localização de tal indicação deve ser escolhida segundo as seguintes regras:
    * Caso o titulo do _commit_(e.g. primeira linha) suporte a inserção da indicação sem quebrar a regra de [72 caracteres](#line-rule), coloque um ';' ao final da mensagem seguido da indicação. Ex:

   > Fix a bug in the person's crud; refs #16

   * Caso contrário use uma linha separada para colocar a indicação. Ex:

   > Implement the search algorithm for cases in which the input is greather than 20

   > refs: #15, #17.