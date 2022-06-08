# MoSCoW

## 1. Introdução

<p align="justify">
O MoSCoW, conhecido como o framework de priorização, funciona entendendo a ideia de que todos os requisitos do projeto podem ser considerados importantes, mas devem ser priorizados para dar os maiores benefícios no prazo mais rápido possível.
</p>
<p align="justify">
O termo MoSCoW é um acrônimo em inglês derivado da primeira letra de cada uma das quatro categorias com os “Os” no meio para fazer a palavra ser pronunciável. Fica assim:
</p>


- Must Have (Tenho que fazer)
- Should Have (Devo fazer)
- Could Have (Poderia fazer)
- Won’t Have (Não vou fazer)

## 2. Metodologia

### 2.1 Ordem de priorização

<p align="justify">
Para organizar os requisitos por ordem de priorização, será utilizado a técnica MoSCoW, que já foi citado anteriormente. Os requisitos serão divididos a partir das seguintes categorias:
</p>

- Must: quando o requisito for essencial para o funcionamento da projeto.
- Should: quando o requisito for importante para o projeto.
- Could: quando o requisito não tem grandes necessidades de ser implementado, apenas se tiver tempo e recursos.
- Won't: quando o requisito não precisa ser implementa no momento, mas seria uma boa melhoria para o futuro.

### 2.1 Nomenclatura dos requisitos

<p align="justify">
Para organizar os requisitos de acordo com funcionais, não funcionais e especiais que são interligados a assinatura do Amazon Prime usaremos as seguintes nomenclaturas.
</p>

- Requisito Funcional - RF
- Requisito Não Funcional - RNF
- Requisito Funcional Amazon Prime - RFAP


#### 2.1.1
<p align="justify">
Diferença entre RF Requisito Funcional e RFAP Requisito Funcional Amazon Prime.
</p>

- RF : Requisito que  aborda a plataforma Prime Video.
- RFAP : Requisito que intercala a Plataforma de streaming Prime video com o Serviço Amazon prime.

## 3. Resultados

### 3.1 Requisitos Funcionais

| Código | Requisito| Prioridade |
|--|--|--|
|RFAP01| O usuário deve conseguir Criar conta |Must|
|RFAP02| O usuário deve conseguir Cancelar assinatura do Amazon prime |Must|
|RFAP03| O usuário pode alterar dados da conta |Must|
|RF01| O usuário deve conseguir visualizar os termos e aviso de privacidade |Must|
|RF02| O usuário deve ter a opção de ocultar uma serie/filme da sua tela inicial |Should|
|RF03| O usuário deve ter a opção de ver pedidos |Should|
|RF04| O usuário deve poder remover títulos da sua lista |Must|
|RF05| O usuário deve ser capaz de comprar conteúdo extra |Must|
|RF06| O usuário deve ser capaz de registrar seu feedback sobre titulo |Should|
|RF07| O usuário deve poder acessar a página de ajuda da plataforma|Must|
|RF08| O usuário deve ser capaz de passar para o proximo episódio ainda na reprodução do atual|Should|
|RF09| O usuário deve poder escolher qual episódio assistir de um título |Must|
|RF10| O usuário deve ser capaz de desabilitar a reprodução automática |Should|
|RF11| O usuário deve ser capaz de visualizar títulos recomendados |Should|
|RF12| O usuário deve ser capaz de assistir ao trailer dos títulos |Should|
|RF13| O usuário deve ser capaz de pular a abertura dos titulos |Should|
|RF14| O usuario deve conseguir ver quais filmes/series ele assistiu anteriormente |Should|
|RF15| O usuário deve poder escolher qual temporada assistir de um título |Must|
|RF16|O usuário deve poder adicionar novos perfis à sua conta|Must|
|RF17|O usuário deve poder alterar sua foto de perfil|Could|
|RF18|O usuário deve poder adicionar títulos à sua lista|Must|
|RF19|O usuário deve ter a opção de realizar uma busca|Must|
|RF20|O usuário deve poder filtrar a sua busca|Must|
|RF21|O usuário deve ter a opção de alterar os meios de pagamento|Must|
|RF22|O usuário deve ser capaz de baixar os títulos|Could|
|RF23|O usuário deve ser capaz de escolher o idioma de áudio|Must|
|RF24|O usuário deve ser capaz de escolher o idioma da legenda|Must|
|RF25|O usuário deve ser capaz de tirar a legenda|Must|
|RF26|O usuário deve poder escolher a qualidade do vídeo|Should|
|RF27|O usuário deve poder usar a opção de tela cheia|Must|
|RF28|O usuário deve poder realizar login na plataforma|Must|
|RF29|O usuário deve poder realizar logout na plataforma|Must|
|RF30| O usuário pode excluir perfis|Must|
|RF31| O usuário pode usar o Watch party|Could|
|RF32| O usuário pode pode alugar canais, filmes e series|Should|
|RF33| O usuário pode pode renovar canais, filmes e series|Should|
|RF34| O usuário pode cancelar alugar canais, filmes e series|Should|
|RF35| O usuário pode pode ocultar vídeos|Could|
|RF36| O usuário pode desvincular os dispositivos |Must|
|RF37| O usuário pode excluir historico de navegação|Won't|
|RF38| O usuário pode ver informações dos atores |Won't|
|RF39| O usuário pode ver informações da conta |Won't|
|RF40| O usuário pode diminuir o consumo de dados|Should|
|RF41| O usuário pode ver detalhes da obra |Should|
|RF42| O usuário deve conseguir acessar um título pelo nome completo ou apenas parte dele |Must|
|RF43| O usuário deve poder criar um perfil infantil |Must|
|RF44| O usuário pode receber recomendações de conteúdo |Must|

<center>
Tabela 1: Requisitos funcionais.
</center>

### 3.2 Requisitos Não Funcionais

| Código | Requisito| Prioridade |
|--|--|--|
|RNF1| O sistema deve ser multiplataforma |Must|
|RNF2| O sistema deve proporcionar uma aba com sugestões para o usuário logado|Should|
|RNF3| O sistema deve oferecer a opção de impedir downloads usando dados móveis |Should|
|RNF4| O sistema deve manter o tempo de filme ou série já assistido para que o usuário possa continuar assistindo posteriormente |Must|
|RNF5|O sistema deve restringir alguns títulos para perfis infantis|Must|
|RNF6|O sistema deve possuir a função de reprodução automática|Should|
|RNF7|O sistema deve ser responsivo|Must|
|RNF8|O sistema deve possuir uma boa conexão com o servidor|Must|

<center>
Tabela 2: Requisitos não funcionais.
</center>


## 4. Referências

Pires, Raphael. Aprenda a usar a técnica MoSCoW nos projetos da sua agência. Disponível em: <https://rockcontent.com/br/blog/metodo-moscow/>. Acesso em: 20 de fev. de 2022.

CARVALHO, Henrique. O framework de priorizacao: MoSCoW. Disponível em: <https://vidadeproduto.com.br/framework-moscow/#O_framework_MoSCoW/>. Acesso em: 20 de fev. de 2022.


## 5. Histórico de Versionamento

|Versão|Data de modificação|Descrição da modificação|Autor|Revisor|
|-|-|-|-|-|
|1.0|20/02/2022|Criação do MoSCoW|[Lameque Fernandes](https://github.com/lamequefernandes)|[Antonio Igor](https://github.com/antonioigorcarvalho), [Douglas Monteles](https://github.com/douglasmonteles) e [Erick Levy](https://github.com/ericklevy)|
|1.1|23/03/2022 |Remodulamento do MosCow|[Erick Levy](https://github.com/ericklevy)| [Antonio Igor](https://github.com/antonioigorcarvalho) |
|1.2|22/04/2022| Alteração na metodologia |[Lameque Fernandes](https://github.com/lamequefernandes)| [Antonio Igor](https://github.com/antonioigorcarvalho) e [Erick Levy](https://github.com/ericklevy) |
|1.3|22/04/2022 |Adição da Diferenças dos Requisitos Funcionais|[Erick Levy](https://github.com/ericklevy)| [Antonio Igor](https://github.com/antonioigorcarvalho) |


