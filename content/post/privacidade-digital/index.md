---
title: 'A toca do coelho da privacidade digital'
subtitle: 'Não podemos confiar na liberdade quando ela não está em nossas mãos'
date: 2023-12-17
math: true
highlight: true
image:
  placement: 2
---

Você talvez não saiba, mas as grandes corporações e as grandes nações possuem diversos métodos e subterfúgios para invadir sua privacidade e utilizar dos recursos tecnológicos como instrumentos de controle social.

Pessoas como Edward Snowden nos deixam claro a profundidade da toca do coelho, no entanto, **comecemos pelo começo**.

## Começando pelo começo

Você provavelmente chegou até aqui através de um navegador ou aplicativo, portanto, tenho algumas perguntas para você:

- Qual **navegador** você utiliza?
- Qual **motor de busca** você utiliza?
- Você usa uma conta conectadas a **serviços do Google** em seu navegador?

E também algumas perguntas sobre o dispositivo que você está utilizando:

- Qual **sistema operacional** você está utilizando?
- Qual **hardware** você está utilizando?

### Navegadores e motores de busca

Se você utiliza **Google Chrome** ou **Microsoft Edge**, por exemplo, saiba que o Google e a Microsoft coletam seus dados, no entanto, sabem o que você está fazendo no navegador.

Se você utiliza um navegador com foco na privacidade como o **Mozilla Firefox** e utiliza o Google como motor de busca e/ou utiliza os serviços Google, saiba que _não faz diferença_, o Google vai continuar coletando dados da maioria dos sites que você visitar.

Se você utiliza um navegador e um motor de busca que respeitam sua privacidade, utiliza um bloqueador de anúncios e não utiliza os serviços Google, ainda assim você talvez possa ser identificado de outras formas, tais como seu **endereço IP**, **cookies** e por métodos mais avançados como _Fingerprinting_.

Ferramentas de _Fingerprint_ são capazes de coletar dados como seu **Sistema Operacional** e seu **idioma**, o **navegador** que você está utilizando, **extensões** instaladas no navegador e muito mais. Com essas informações, é possível criar uma impressão digital única que identifique o usuário.

Teste você mesmo [`clicando aqui`](https://fingerprint.com/demo/).

### Sistemas Operacionais

#### Windows (Microsoft)

Windows é uma caixa preta, seu código-fonte é fechado e se comporta como _spyware_, principalmente nas versões mais recentes. Possui diversos serviços de telemetria que coletam seus dados e os vendem para empresas de anúncios.

Recomendo que assista [`esse vídeo`](https://www.youtube.com/watch?v=IT4vDfA_4NI) que demonstra o aumento da coleta de dados do Windows, comparando o Windows XP com o 11.

#### MacOS (Apple)

Enquanto na questão segurança o MacOS seja sem dúvidas mais seguro, seu código-fonte também é fechado e possui serviços de telemetria que coletam seus dados, assim como o **Windows**.

#### Linux

Caso você esteja usando Linux, você provavelmente já sabe: é mais seguro e depende da distro para analisarmos questões de privacidade. No entanto, a descida pela toca do coelho ainda **não acabou**, as outras perguntas precisam ser respondidas.

### Hardware

#### <mark>Smartphones</mark>

Hoje em dia os smartphones são muito mais utilizados que os desktops, principalmente para o consumo de **redes sociais** e **aplicativos de mensagens**. Caso você esteja usando um smartphone, grandes chances são que seu sistema operacional seja **Android** ou **iOS**.

##### Android (Google)

Caso você esteja utilizando Android, você deve saber que é um sistema operacional do Google que podemos considerar de código fechado, visto que o sistema instalado na maioria dos celulares dependem de **serviços proprietários** do Google para funcionar. O Google possui acesso a tudo o que você faz no celular.

##### iOS (Apple)

O sistema iOS é ainda mais fechado que o Android e e seus dados estão sendo coletados pela **Apple**.

#### <mark>Computadores</mark>

Você pode ser um usuário minucioso de Linux e pensar que está livre das mãos das grandes corporações, no entanto, eu tenho uma pergunta para você: <mark>qual processador você está utilizando? Intel? AMD?</mark>
Aqui, você vai perceber que a toca do coelho é mais profunda do que parece.

##### Intel

Se você utiliza um processador Intel fabricado após 2008, ele possui um componente chamado _Intel Management Engine_ que é um subsistema autônomo que roda o sistema operacional **MINIX** paralelamente em uma camada abaixo do seu sistema operacional normal (Windows, MacOS, Linux etc.). Esse subsistema possui acesso à Internet e possui controle do que você faz em seu computador. As capacidades desse subsistema não terminam por aí, ele é capaz de operar mesmo que seu computador esteja desligado, mas conectado a uma fonte de energia.

##### AMD

Bom, mas eu utilizo processador AMD, então devo estar bem, certo? **ERRADO!** Os processadores AMD possuem um mecanismo semelhante conhecido como PSP (_Platform Security Processor_) que fora introduzido em 2013.

Eu não posso ser injusto e dizer que é simples invadir um computador através desses mecanismos, depende de uma série de fatores, [`veja aqui`](https://mjg59.dreamwidth.org/48429.html) mais sobre a vulnerabildade do Intel ME.
Ainda assim, é bastante preocupante e sem dúvidas, uma ameaça para a privacidade digital.

## Lembrai, lembrai de Edward Snowden

No começo desse artigo citei Snowden e disse que ele deixou claro até onde a toca do coelho vai...

Snowden incomodou muita gente revelando a capacidade de espionagem da NSA (Agência de Segurança Nacional dos EUA) e deixou claro que a agência possui um backdoor em todos os principais sistemas computacionais que utilizamos e conseguem acesso direto aos dados sem passar por pedidos judiciais.

Isso foi revelado pelo vazamento dos programas de vigilância **PRISM** e **XKEYSCORE** da NSA.

{{<figure src="prism.jpg" caption="Programa PRISM e a coleta de dados de grandes provedores" id="prism">}}

## Por que eu me preocuparia com tudo isso?

É muito comum as pessoas não se importarem com esse assunto por pensarem que por não ter influência nada disso importa, afinal há tantas pessoas por aí, por que se importariam justamente com seus dados, não é mesmo?

Um problema claro ao abdicar de sua privacidade é que certamente você estará mais vulnerável a ataques hackers, ataques de engenharia social e ataques que utilizam de inteligência artificial, sendo esse último cada vez mais comum e com hardwares cada vez mais poderosos, está se tornando questão de tempo para termos muita dificuldade em diferenciar o que é real e o que não é.

<mark>"Uma provocação: imagine que um político com uma grande esfera de poder seja chantageado, pois não tomou cuidado com sua privacidade no passado. Seria um grande problema, não?" Será que isso já não acontece?"</mark>

O problema não para por aí, ao não se preocupar com essa questão, você provavelmente aceitará mais programas que invadirão sua privacidade e não se dará conta da gravidade.

### Vamos falar de dinheiro? Você certamente se preocupa com ele! Não?

É quase certo que o dinheiro da forma que conhecemos hoje irá mudar ainda nessa década e o papel-moeda desaparecerá; no Brasil, já estão trabalhando para isso: **Drex**, o real digital.

Com a implantação do Drex, toda transação dependerá de uma instituição financeira e por ser uma moeda centralizada e regulada pelo Banco Central, teremos uma entidade poderosa com controle total e conhecimento pleno do que acontece com o dinheiro a todo o momento.

<mark>Imagine um Brasil distópico em que ditadores tomem o poder e o seu Zé (nosso personagem fictício) resolva participar de uma manifestação contra o governo. Nesse Brasil distópico, o seu Zé foi flagrado por sistemas de vigilância e seu dinheiro e das pessoas que o apoiaram em redes sociais foi congelado.</mark>

## O que quero dizer com isso tudo?

Não podemos confiar na liberdade quando ela não está em nossas mãos. Ao permitirmos dispositivos que coletam nossos dados e nos monitoram em troca da conveniência e simplicidade do dia a dia, paradoxalmente renunciamos nossas liberdades.

É chato, não é nada conveniente na maioria das vezes, requer dedicação, mas recomendo que você faça hoje o que você pode com os recursos que você possui para ter mais privacidade. Recomendo que comece por [`aqui`](https://www.privacyguides.org/).

Privacidade é um assunto extremamente amplo. Eu poderia escrever horas de conteúdo e certamente faltaria abordar mais pontos, no entanto, espero estar contribuindo de alguma forma.

**Deixando claro: o que escrevo aqui são minha e somente minha opinião e reflexões.**
