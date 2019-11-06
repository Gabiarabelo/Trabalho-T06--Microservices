# 
Nome: Gabriela Alves Rabelo
RA: 1510033606

Trabalho-T06--Microservices


Um caso real de implementação de microserviços é o uber. Quando ele estava entrando no mercado, criaram sua solução para uma única oferta em uma única cidade. Mas, à medida que a empresa se expandia, seu sistema, baseado em uma arquitetura monolítica, começou a causar problemas com escalabilidade e integração contínua.

Problemas:
Todos os recursos tiveram que ser reconstruídos, implantados e testados repetidamente para atualizar um único recurso.
A correção de bugs se tornou extremamente difícil em um único repositório, pois os desenvolvedores tiveram que mudar o código repetidamente.
Escalar os recursos simultaneamente com a introdução de novos recursos em todo o mundo foi bastante difícil de ser tratado em conjunto.
Solução:
A principal mudança é a introdução do API Gateway através na qual todos os motoristas e passageiros estão conectados. No API Gateway, todos os pontos internos são conectados, como gerenciamento de passageiros, gerenciamento de motoristas, gerenciamento de viagens e outros.
Os códigos são separados individualmente, executando funcionalidades separadas.
Agora, todos os recursos foram redimensionados individualmente, ou seja, a interdependência entre cada recurso foi removida.
Dessa forma, o Uber se beneficiou mudando sua arquitetura de monolítico para microsserviços.
