# Explorando os Recursos de IA Generativa com Copilot e OpenAI

## Descrição

Este é um projeto que via explorar as funcionalidades do Copilot Studio, porém não tenho licença para uso, mas apliquei o aprendizado na versão gratuida do Copilot.

## Tecnologias e Técnicas Utilizadas 

* Microsoft Copilot
* Prompts

## Atividade

No Copilot Studio eu posso criar agentes de IA que usam bases de conhecimento especificas e respondem apenas consultando essa base, consigo fazer algo semelhabte com a IA Generativa Copilot através de prompts, criei um chat que me responderá apenas noticias sobre politica consultando 4 sites como banco de informações.

###Prompt###

Olá Copilot, quero que me responda nesse chat apenas perguntas relacionadas a noticias da politica, use apenas os sites abaixo como fonte. 

https://oantagonista.com.br/ 
https://www.estadao.com.br/ 
https://www.revistaoeste.com/ 
https://www.msn.com/pt-br 

Se eu perguntar qualquer outra coisa que não seja relacionado a politica responda com "Me desculpe, esse não é o assunto do site, faça uma pergunta sobre politica."


```
Durante as aulas aprendemos a otimizar os prompts usando a seguinte estrutura

“Contexto” -> Contexto: Todo o contexto do que eu quero que seja feito, que a IA busque lá dentro, um livro inteiro.
###Pergunta### -> Pergunta: O que eu quero perguntar
<Comportamento> -> Comportamento: Como eu quero a resposta, devolva isso no formato X.

Agora um exemplo da aplicação desse prompt

“Foi descoberto recente um escândalo de corrupção no INSS, quero mais detalhes” 

###Quando começou a fraude? Como foi descoberto? Como isso aconteceu nos governos Lula e Bolsonaro?### 

<Separe a resposta por site, por exemplo Antagonista e abaixo mostre as noticias mais relevantes, depois Estadao e abaixo mostre as noticias mais relevantes e assim por diante>
```

## Bootcamp Microsoft Copilot IA
Link: https://web.dio.me/track/microsoft-copilot-ai
