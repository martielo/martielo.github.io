---
title: 'Complexidade everywhere'
subtitle: 'Você realmente está atacando a complexidade? Ou está ajudando a criá-la? 🤔'
date: 2022-06-02
math: true
highlight: true
image:
  placement: 2
---

## O que quero dizer com isso?
Trabalhar em consultoria me traz a oportunidade de atuar em vários projetos de empresas completamente diferentes e, embora difiram, certas práticas parecem não mudar.

Percebo em diversos lugares aplicações sendo criadas utilizando arquitetura de N camadas e com conceitos de DDD. Por que será? Porque virou `boilerplate`! Tornou-se sinônimo de "projeto bem arquiteturado", logo, TODO projeto segue essa estrutura, dois mais simples ao mais complexos.

#### O DDD existe para nos ajudar a [**atacar as complexidades no coração do software**](https://www.amazon.com.br/Domain-Driven-Design-Eric-Evans/dp/8550800651)...
...quando elas existem! E não para justificar a criação de um projeto com inúmeras camadas e com seus conceitos "*só porque é legal e/ou porque parece ser mais certo*".

Se você é desenvolvedor, já deve ter encontrado um projeto com uma estrutura mais ou menos assim (Se é desenvolvedor .NET, 99% são as chances que sim):

    [Empresa].[Projeto].[API] -> Controllers
    [Empresa].[Projeto].[Domain] -> Entities
    [Empresa].[Projeto].[Application] -> Services, Handlers
    [Empresa].[Projeto].[Infrastructure] -> Repositories, Context


Vamos supor que os projetos mais simples de uma empresa sejam CRUDs, não há regras de negócio, apenas validações de inputs. O "Domain" `(que não existe)` naturalmente só vai conter Modelos anêmicos. Aqui é apenas CRUD, não tem como dar muito errado... **Por que então gerar toda essa complexidade?**

Agora vamos supor um cenário de um projeto mais complexo: uma empresa que tenha necessidades muito específicas com regras de negócio que evoluam constantemente. O projeto precisa evoluir conforme a empresa evolui e nesse caso é necessário tratar o Domínio `(que dessa vez realmente existe)` com muita delicadeza.

`Ocorre que muito provalvemente, o suposto projeto mais complexo será tratado como o projeto mais simples!`

-- Mas agora a complexidade existe. Faria sentido criar as N camadas e "usar" DDD, não?

NÃO! A ideia é **atacar** a complexidade, não gerá-la. Criar camadas e mais camadas e utilizar conceitos de DDD como foi feito nos projeto CRUDs, não resolve NADA por si só. É preciso entender os PORQUÊS das escolhas.

Além do mais, muito provavelmente o projeto será executado como os mais simples:

    1. 'Criar o projeto com o Boilerplate ("N Camadas" + "DDD")'
    2. 'Criar Models'
    3. 'Criar tabelas no banco de dados'
    4. 'Criar services e mais services'
    5. 'Repetir os itens [2, 3, 4, 5]'

Diagamos que esse projeto realmente exista e a primeira entrega tenha sido um sucesso...
#### ...MAS VÍRGULA
Acontece que o Domínio é complexo! Ele vai evoluir, mais **processos** surgirão e o projeto e nem a equipe estão preparados para isso. A Domain Model é anêmica, os processos e regras de negócio estão acoplados com serviços de aplicação. Como serão as próximas entregas dessa equipe?

Pela minha experência, posso dizer que geralmente termina com a famosa [`Big Ball of Mud`](https://en.wikipedia.org/wiki/Big_ball_of_mud).

## Conclusão
Mantenha simples o que é para ser simples (`Keep it simple, stupid`)! Lembre-se que não existe bala de prata e trate de complexidades como elas devem ser tratadas. Uma dica: `foque no domínio`.

Sim, a palavra "complexid4de" foi utilizada 7 vezes, e essa não é a oitava.