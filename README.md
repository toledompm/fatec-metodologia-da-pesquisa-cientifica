# Metodologia da Pesquisa Científica

Problema
--------

  Documentar projetos JavaScript automaticamente, através de trechos de comentários, marcados por decorators. O output deverá ser no formato Latex, com o objetivo de integrar facilmente com artigos científicos em desenvolvimento.

Motivação
---------
   Documentação não é um dos processos mais glamurosos da programação, e geralmente é deixado de lado até o projeto ser finalizado. Além de normalmente ser feita através de ferramentas externas, facilitando que partes sejam omitidas, e alterações sem atualizar a documentação.
   https://uxdesign.cc/documenting-is-designing-how-documentation-drives-better-design-outcomes-3ebd87a33d57
   
   No entanto, é uma das partes mais importantes do desenvolvimento. O tempo gasto documentando um projeto é resgatado em diversas ocasiões, como quando um novo integrante precisa se situar no projeto, ou quando um cliente tem sua dúvida respondida por uma rápida pesquisa.
   https://medium.com/eloquent-coding/do-developers-dream-of-self-documenting-code-ca64d472197a

   Os problemas apresentados não são novidade, e já existem diversas ferramentas que solucionam muitos deles. No entanto, os documentos produzidos são geralmente voltados a outros desenvolvedores. Deixando uma lacuna quando o objetivo da documentação for para fins acadêmicos.
   https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1006561

Proposta de Solução
-------------------

  Será criado um pacote NPM que através de anotações no código, irá gerar um documento na forma ABNT com os comentários de cada módulo.

  Tratar documentação como código nos ajuda a solucionar um problema grande de documentação por versão. Ao utilizar ferramentas de versionamento de software como git, é possível gerar documentos a partir de releases antigos, pois a documentação do código antigo está diretamente atrelada a ele.
  https://dev.to/nicoespeon/where-should-you-put-the-documentation-18gg
  
TO-DO
-----
Estudar referencias:
   - https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1006561

