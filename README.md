# O Papel dos Bancos de Dados SQL e NoSQL na Engenharia de Dados
Speaker: Leonardo Cestarolli - Banco Carrefour

Contexto geral sobre o uso do banco de dados na atualidade
- Tecnologias de banco de dados tem várias, sendo necessário entender o propósito de cada um para fazer uso.

O que é SQL e NoSQL?
- Banco Relacional: tipo de dados que tem relacionamento entre si e tem normalização, consistência, esquema rígido e você sabe exatamente o que vai armazenar. Ter um banco muito bem definido.
- Banco NoSQL: Not Only Structured Query Language. Alternativa aos bancos relacionais, com capacidades adicionais. Necessidades diferentes e informações não relacionadas, estrutura de dados não-rígida.

O NoSQL não foi criado para substituir o SQL
- A ideia é que não substitua de fato. São complementares. Foram criados para resolver problemas que os relacionais não resolvem. Um ponto interessante, é a consulta, que pode se tornar bem mais complexa no relacional.

Como se consulta um dado armazenado no NoSQL?
- É preciso ter um conjunto de chaves interessantes, é preciso tomar cuidado e ser feita desde o início. A aplicação tem que considerar as consultas e estar preparado para isso.
- É preciso pensar na modelagem também.

Conhecer um SGBD de cada tipo é suficiente para iniciar?
- É inviável aprender todos os tipos, mas é importante conhecer os conceitos e os propósitos para que quando de fato for precisar, você já saiba qual utilizar.
- Após escolher o banco é necessário conhecer mais a fundo a tecnologia e suas capacidades.
- Não existe só um caminho.
- Estabeleça bem os critérios técnicos que vão embasar uma decisão arquitetural.

No Banco Carrefour, quais os SGBDs mais utilizados?
- Contexto híbrido, com Oracle, infraestrutura de Big Data e um pouco de Mongo.

Evolução da arquitetura de sistemas e transições de estruturas
- Quando começamos do zero temos mais liberdade de escolha, a partir do momento em que já temos algo estabelecido, precisamos pensar em uma transição que seja o mais suável possível, para que não seja necessário parar.
- Sobre as tecnologias de núvem, mais do que a tecnologia tem que pensar na estratégia.

Sobre DataLake e Databricks
- Ajudam a manter uma consistência dentro de uma datalake, com segurança e com baixo custo visto de armazenamento e processamento dado o volume de dados.

Quais os maiores desafios na hora de realizar o ETL?
- É a parte de manipulação forte de dados. 
- Mais de mil processos de ETL.

O tipo de banco de dados influencia na complexidade?
- o que de fato será armazenado dentro do banco de dados.
- Precisa ter uma forma de definição de como esses dados serão consultados.

Como é gerada a demanda dos dado e quem define quais dados serão coletados?
- Times mais estruturantes com capacidades técnicas trabalham bem próximas.

Engenheiro e Cientista de dados
- São complementares. O engenheiro tá mais ligado a preparação dos dados. E o cientista tá mais ligado com modelos.

Deficiências em pessoas com skill em Estatística
- É importante essa skill. Matemática e estatística são a base, assim como de negócios e outros.

Quais dicas para quem quer ser Engenheiro de dados do Banco Carrefour?
- A ferramenta em si não é o principal é o meio para se atingir os seus objetivos. 
- Precisa ter um conhecimento bem amplo de todas as camadas.
- Curiosidade, pois as coisas vão surgir a todo momento. Olhar crítico, a tecnologia para resolver o problema que a gente precisa. Técnicas ETL, fluxos com Spark, conhecimento em GCP, fluxo de dados.