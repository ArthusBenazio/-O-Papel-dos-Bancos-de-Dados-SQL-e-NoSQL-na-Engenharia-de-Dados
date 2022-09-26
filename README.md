# O Papel dos Bancos de Dados SQL e NoSQL na Engenharia de Dados
Contexto geral sobre o uso banco de dados na atualidade
As tecnologias de banco de dados tem muitos tipos do relacional como do não relacional mas dentro desses dois mundos tem muitas opções, o segredo é entender o conceito de cada um desses bancos, o propósito para que foi pensado e assim fazer o uso da ferramenta certa para o problema.

Na engenharia de dados acaba tendo diversos formatos de arquivos tanto de origem como de destino, formato de dados que devemos armazenar no ambiente de dados.

O Banco de Dados Relacional (SQL) é o que armazena as entidades, permite o relacionamento entre elas, uma consistência e um esquema bem rigido.

O Banco de Dados Não Relacional (NoSQL) é uma alternativa (complemento) aos Bancos Relacionais onde permite o armazenamento das informações não estruturadas e não rígida.

O Banco de Dados NoSQL não substitui os bancos relacionais, ele surgiu para atender o que não era possível fazer num banco relacional.

As consultas de informações em bancos relacionais são bastantes complexas dependendo das quantidades de joins que precisamos fazer, em contrapartida no banco não relacional podemos armazenar a informação de acordo com sua própria consulta onde reduz a complexidade evitando o uso de joins.

A forma da consulta em um banco de dados NoSQL deve ser pensada no início, definindo as chaves e as formas de como será efetuada a consulta da informação, inclusive para não se armazenar de apenas uma única forma. Outro ponto, a aplicação deve saber lidar com a falta de previsibilidade de um esquema, que tipos de informações pode sere, desprezadas ou não.

Devemos entender o conceito de cada banco de dados, para que eles servem e quando precisar de fato fazer o uso. Com o conceito e com uma visão prévia de outro banco de dados, de fato a curva de aprendizado se torna menor e bem mais simples.

Conhecer os tipos de bancos NoSQL é importante como por exemplo:

Chave e valor
Documentos
Colunares
Grafos
Quando fala das propriedades ACID, precisa de um contexto de consistência:

ATOMICIDADE - garante que as transações que estamos fazendo no banco não relacional, ter todas elas estão sendo executadas ou não executará nenhuma, com isso sempre segue o caminho da consistência.
CONSISTÊNCIA - garante que o dado estará consistente para outro como foi inserido.
ISOLAMENTO - garante que uma transação não interferirá na outra.
DURABILIDADE - a informação que foi armazenada não perderá.
As arquiteturas necessitam de evoluções constantes e para fazer uma evolução não precisamos esquecer da transição disso, quando começa de um ambiente do zero a gente tem mais liberdade de fazer as escolhas e por onde quer seguir. A partir do momento que já tem um ambiente estabelecido, buscamos uma evolução de como a transição seja a mais suave possível para que não pare o nosso dia a dia.

O maior desafio quando fala do mundo de dados essa parte de manipulação de dados (ETL), seja na transformação, ingestão, gestão, processamento, preparação dos dados para que fiquem disponibilizados pelas camadas de processamento, ou seja, tudo envolve uma manipulação forte de dados, e isso se traduzem em diversas rotinas onde podem ser rotinas onlines, schedulares de tempos diferentes, diárias, semanais, mensais e enfim.

Diferença entre Engenheiro de Dados e Cientista de Dados
Engenheiro de Dados está mais ligado a preparação da informação, é uma pessoa que precisa de um conhecimento técnico para conseguir coletar a informação, preparar, armazenar e deixar disponível para que os cientistas consigam utilizar.

Cientista de Dados é uma skill ligado a criação de modelos, onde aplicará algum tipo de processamento na informação disponibilizada pelo engenheiro e isso gerará algum valor associado ao negócio.
