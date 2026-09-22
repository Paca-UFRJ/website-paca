+++
date = 2026-02-11
title = "Uma prova do algoritmo de Brzozowski via álgebras de Kleene"

[extra]
authors = "Matheus do Ó, Hugo Musso Gualandi"
where = "Trabalho de Conclusão de Curso, BCC/UFRJ"
url = "http://hdl.handle.net/11422/29128"
+++
Autômatos finitos são objetos recursivamente definidos, o que torna natural provarmos suas propriedades através de indução. Em especial, muitos problemas de teoria dos autômatos necessitam de identificar se dois autômatos diferentes têm a mesma linguagem, isto é, se são equivalentes. Tais provas geralmente são feitas através de indução no comprimento dos caminhos, além de serem feitas em duas direções, visto que precisamos mostrar que todo caminho válido em um autômato tem um equivalente noutro e vice-versa. Estas provas apresentam dois problemas principais: uma escolha ruim de caso base e hipótese indutiva pode tornar provas por indução desnecessariamente complicadas ou até incorretas; provas de ida-e-volta podem ser desafiadoras e, neste contexto, cada caminho do autômato precisa ter seu equivalente encontrado em um autômato diferente. Uma alternativa para ambos problemas é o teorema da fusão, que torna provas indutivas em provas por igualdade, simplificando-as e removendo preocupações herdadas de provas indutivas. Neste trabalho, buscamos demonstrar como álgebras de Kleene e o teorema da fusão podem conversar bem com teoria dos autômatos finitos e fazemos isto focando em um problema em específico: minimização de autômatos finitos. Trazemos a primeira prova da corretude do algoritmo de Brzozowski à luz do teorema da fusão e via formalismo matricial.

