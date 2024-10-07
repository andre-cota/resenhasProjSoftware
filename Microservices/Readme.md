# Resenha sobre o Artigo de Martin Fowler – Microservices 

 

O artigo microservices abrange de forma prática alguns temas relacionados sobre o conceito de microserviço, como o próprio nome já diz. Os principais tópicos sobre o assunto são: 

*O que são e suas características 
*Componetização em Serviço  
*Descentralização de gorvernança e gerenciamento de dados 
*Automatização de Infraestrutura  

 

No início somos introduzidos à uma forma simplificada do que seria essa arquitetura “particular way of designing software applications as suites of independently deployable services”. É falado que um conceito novo de arquitetura e com isso não há muita informação sobre o que é o estilo de microserviço e como deve ser realizado. 

Para ser mais fácil de interpretar e de se analisar, é comparado diretamente ao modelo de monolito, que é a forma oposta de se realizar os serviços, enquanto os monolitos são aplicações únicas e indivisíveis que precisam ser redesenvolvidas e implantadas inteiramente a cada mudança, os microserviços são modulares e permitem que apenas partes específicas sejam alteradas e implantadas, resultando em mais flexibilidade.  

Os principais pontos positivos em torno das características dos microserviços, citadas no artigo giram em torno de: componentização via serviços (os sistemas são divididos em serviços independentes, cada um gerenciável e atualizável individualmente), organização em torno de capacidades de negócios (os microserviços são divididos conforme áreas funcionais de negócios, o que melhora a autonomia das equipes) e divisão como produto e não projeto(ao invés de ver o software como algo a ser entregue e depois abandonado, a abordagem é contínua, onde a equipe de desenvolvimento é responsável por seu ciclo de vida completo). 

Um tópico importante a ser mencionado é sobre o design para falha e monitoramento. É informado que como os microserviços são distribuídos, o sistema deve ser capaz de lidar com falhas de serviço de forma graciosa, utilizando ferramentas de monitoramento em tempo real para verificar o funcionamento de cada serviço. 

A conclusão apresentada no texto é de otimismo, mas com cautela. Os autores reconhecem que a arquitetura de microserviços tem mostrado resultados positivos em vários contextos, especialmente em empresas como Amazon e Netflix, que têm pioneirado sua adoção. Eles destacam que essa abordagem permite maior modularidade, escalabilidade e flexibilidade. No entanto, ainda é cedo para dizer com certeza se os microserviços são o futuro definitivo da arquitetura de software. Isso porque muitas das consequências de decisões arquiteturais, boas ou ruins, só se tornam visíveis após vários anos. A arquitetura de microserviços pode introduzir complexidades adicionais, especialmente na comunicação entre serviços e na necessidade de refatorações difíceis entre componentes distribuídos. 
