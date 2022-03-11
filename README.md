## stream-java

Sequencia de elementos advinda de uma fonte de dados que oferece suporte a "operações agregadas".  
• Fonte de dados: coleção, array, função de iteração, recurso de E/S

Características  
• Stream é uma solução para processar sequências de dados de forma:  
• Declarativa (iteração interna: escondida do programador)  
• Parallel-friendly (imutável -> thread safe)  
• Sem efeitos colaterais  
• Sob demanda (lazy evaluation)  
• Acesso sequencial (não há índices)  
• Single-use: só pode ser "usada" uma vez  
• Pipeline: operações em streams retornam novas streams. Então é possível criar uma cadeia de operações (fluxo de processamento).  

Doc: http://www.oracle.com/technetwork/pt/articles/java/streams-api-java-8-3410098-ptb.html

Operações intermediárias  
• filter  
• map  
• flatmap  
• peek  
• distinct  
• sorted  
• skip  
• limit (*)  

short-circuit  
Operações terminais  
• forEach  
• forEachOrdered  
• toArray  
• reduce  
• collect  
• min  
• max  
• count  
• anyMatch ()  
• allMatch ()  
• noneMatch ()  
• findFirst ()  
• findAny (*)  

short-circuit  
