+++
date = 2025-06-16
title = "Otimizações no compilador da linguagem de programacão Pallene"

[extra]
authors = "Gabriel de Souza Ferreira, Hugo Musso Gualandi"
where = "Trabalho de Conclusão de Curso, BCC/UFRJ"
url = "http://hdl.handle.net/11422/27181"
+++
Pallene é uma linguagem de programação criada para facilitar a otimização de programas
escritos em Lua. O compilador de Pallene gera código C que por sua vez é compilado
em bibliotecas que são usadas dentro de Lua. Apesar de Pallene se aproveitar de otimizações feitas pelo compilador de C, ainda existem oportunidades de otimização que só
podem ser identificadas a nı́vel de Pallene. Neste trabalho, implementamos algumas dessas otimizações no compilador de Pallene. As otimizações que implementamos realocam e
eliminam chamadas a funções no código gerado que prejudicam o desempenho do otimizador do compilador C. Também criamos a infraestrutura que facilitará a implementação de
novas otimizações no futuro, o que envolveu mudar a representação intermediária usada
pelo compilador Pallene, e descrevemos como foi o processo de refatoração do código do
compilador.
