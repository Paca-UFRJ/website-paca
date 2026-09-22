+++
date = 2025-12-11
title = "Verificação formal de uma implementação eficiente de UTF-8"

[extra]
authors = "Leonardo Ribeiro Santiago, Hugo Musso Gualandi"
where = "Trabalho de Conclusão de Curso, BCC/UFRJ"
url = "http://hdl.handle.net/11422/28389"
+++
O sistema de codi!cação Unicode é imprescindível para a comunicação global, permitindo que inúmeros idiomas utilizem a mesma representação para serializar todos os caracteres, eliminando a necessidade de conversão. Dentre todos os formatos de codificação definidos pelo consórcio Unicode, certamente o formato ubíquo é o UTF-8, pela sua retrocompatibilidade com ASCII, e capacidade de economizar bytes. Apesar de ser utilizado em mais de 98% das páginas da internet, vários problemas aparecem ao implementar programas de codificação e decodificação de UTF-8 semanticamente corretos, e múltiplas vulnerabilidades estão associadas a aceitar caracteres UTF-8 inválidos erroneamente. Assim, este trabalho utiliza verificação formal através de provadores de teoremas interativos com dois propósitos. Primeiro, será desenvolvido um conjunto de propriedades - a especificação - que são suficientes para afirmar a corretude de um codificador ou decodificador de UTF-8. Com a especificação formalizada, implementamos
um codificador e decodificador, mostrando que esses respeitam todas as propriedades
necessárias para que estejam corretos.
