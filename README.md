# Problema de Josephus #

Trabalho realizado para a disciplina de Estrutura de Dados II, executado na IDE Eclipse C/C++ e MinGW.
Matéria ministrada pelo professor Rafael Nunes, no curso de Ciência da Computação do 4º Período, na Universidade FUMEC.

Desenvolvido por:
* [Vinícius Ferreira](https://www.facebook.com/ferreiravinicius)
* [Natasha Kaweski](http://www.twitter.com/naweskil)

### Versões ###

#### Versão 2.1 ####

* Novas alterações na função principal executaJosephus()
* Programa pronto e em funcionamento!

#### Versão 2.0 ####

* Todas as funções necessárias criadas;
* Funções de auxílio como remove_soldado() e cria_soldado() criadas e funcionando corretamente;
* Trabalho comentado e traduzido.

#### Versão 1.0 ####

* Beginning!

### O que isso faz? ###

Este programa segue a lógica da adedanha de grupo. Segue a historinha do programa:

Problema de Josephus (Tenenbaum, 1989)
* Há um grupo de soldados circundado por uma força inimiga esmagadora. Não há esperanças de vitória sem a chegada de reforços, mas existe apenas um cavalo disponível para escapar. Os soldados entram num acordo para determinar qual deles deverá escapar e trazer ajuda.
* Eles formam um círculo e um número n é sorteado num chapéu.
* Um nome de soldado também é sorteado.
* Começando pelo soldado cujo nome foi sorteado, eles começam a contar ao longo do círculo em sentido horário.
* Quando a contagem alcança n, esse soldado é retirado e a contagem reinicia com o soldado seguinte.
* O processo continua de maneira que, toda vez que n é alcançado, outro soldado sai do círculo.
* Todo soldado retirado do círculo não entra mais na contagem.
* O último soldado que restar deverá montar no cavalo e escapar. 
* Considerando um número n, a ordenação dos soldados no círculo e o soldado a partir do qual começa a contagem, o problema é determinar a sequência na qual os soldados são eliminados do círculo e qual soldado deverá escapar no cavalo.

### Funções utilizadas ###

* `cria_soldado(); // auxiliar`
* `remove_soldado(); // auxiliar`
* `inicializa();`
* `verificaCircVazio();`
* `insereSoldadoNoCirc();`
* `imprimeSoldadosCirc();`
* `verificaQteSoldados();`
* `executaJosephus();`
