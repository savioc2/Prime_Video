# Políticas de Branch

Padronização das branches no projeto. 


## 1. Padronização das Branches

### 1.1 Prefixos:
- ```hotfix```
- ```documentation```

### 1.2 Formato:
```
<prefixo>/assunto
```

Não esquecer de dividir as palavras(sempre minúsculas) do assunto com "-".
Exemplo: 
```
feature/novo-menu
```

### 1.3 Branches:

<p align="justify">
- **Branch main:** Branch que contém o código em nível de produção, será o código mais consolidado existente na aplicação. Nenhum integrante dos times é autorizado a fazer commits diretamente na *main.*
</p>
<p align="justify">
- **Branchs hotfix:** Branches no qual são realizadas correções de bugs São criadas começando com o prefixo **hotfix/**.
Exemplo: ```hotfix#02/correcao-politicas```
</p>
<p align="justify">
- **Branches documentation:** Branches na qual são desenvolvidos os documentos do projeto. São ciradas começando com o prefixo **documentation/**
Exemplo: ```documentation#49/template-documento```
</p>

### 1.4 Princípios:
- Por ser um projeto voltado totalmente para um público brasileiro e por toda equipe ter mais afinidade com o português, foi decidido que todas as braches serão em pt-BR.


## 2. Referências

DULCETTI, Bruno. Padrões e nomenclaturas no Git. *BrunoDulcetti*. Disponível em: <https://www.brunodulcetti.com/padroes-e-nomenclaturas-no-git/>. Acesso em: 14 de fev. de 2022.

Políticas de Branches. Disponível em: <https://fga-eps-mds.github.io/2018.2-ComexStat/docs/politicaBranches>. Acesso em: 14 de fev. de 2022.

HADLER, Mikael. Utilizando o fluxo Git Flow. *Medium*. Disponível em: <https://medium.com/trainingcenter/utilizando-o-fluxo-git-flow-e63d5e0d5e04>. Acesso em: 14 de fev. de 2022.

## 3. Histórico de Versionamento


| Data       | Versão | Descrição                                 | Autor             |
| :--------: | :----: | :----------:                              | :---------------: |
| 14/02/2022 |  1.0   | Criação da política de branch             | [Lameque Fernandes](https://github.com/LamequeFernandes)|
