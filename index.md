
# Resumo

<div style="text-align: justify">
As instituições públicas detêm um grande volume de dados que poderiam ser usados para melhorar os seus serviços. Isso tem motivado um movimento denominado de dados abertos dados. Nesse sentido, o Brasil e outros países têm criado leis que incentivem e obriguem as instituições abrirem seus dados públicos. Um exemplo disso foi um decretou de 2016 que obrigou as instituições federais criarem seus Planos de Dados Abertos. Isso levou a criação de diversos portais de dados abertos. Porém, atualmente esses portais de dados abertos não estão conectados tornando impraticável a consulta de dados entre eles. A conexão destes dados pode ser realizado através de um conjunto de práticas denominadas de dados conectados. O objetivo desse trabalho é desenvolver um repositório de dados utilizando essas práticas denominado DBacademic. Com esse objetivo, os dados abertos de 25 instituições públicas de ensino foram extraídos, transformados e carregados para um repositório de dados conectados. Essa transformação resultou em quase 900 mil triplas que podem ser consultadas através do site dbacademic. 
</div>

# Conjunto de Dados

<div style="text-align: justify">
Neste trabalho identificou-se 45 instituições públicas de ensino com dados abertos, com em média 20 conjuntos de dados cada.

No entanto, para cumprir o propósito do projeto foram selecionados alguns conjuntos de dados pertinentes, estes listados abaixo. 
</div>

| Dados | Descrição |
| :------ | :------ |
| <i>Docente</i> | Informações de cada docente, como nome, descrição pessoal, código, e-email,  áreas de interesses, departamento e a URL para o currículo lattes. |
| <i>Curso</i> | Informações de cada curso, como nome,  área de conhecimento CNPQ, departamento, coordenador, modalidade do curso e título do profissional. |
| <i>Departamento</i> | Nas universidades, usualmente os docentes estão associados a um dado departamento. Então, usualmente essa base de dados tem dados como nome, localidade, chefe e o centro no qual ele está associado e código.|
| <i>Centro</i> | Muitas universidades, existe uma hierarquia superior aos departamentos, no qual eles são associados. Os dados são usualmente, nome, localidade e diretor. |
| <i>Grupos de Pesquisa</i> | Os grupos de pesquisa são grupos de docentes e discentes, que estudam um dado tema, e tem um docente como coordenador. Os dados são usualmente, nome, área de conhecimento e coordenador. |
| <i>Monografias (Trabalhos de Conclusão de Curso)</i> | Informações sobre as monografias (ou trabalho de conclusão) dos discentes, tais como  título, nome do aluno, nome do orientador, nome do curso, ano e data da defesa. |
| <i>Discente</i> | Este conjunto engloba as informações dos alunos ativos, por ingresso ou egressos da universidade. Usualmente, contém poucos atributos, como nome do aluno, matrícula, período de ingresso e nome do curso. |

## Sparql endpoint

* [https://sparql.dbacademic.tech](https://sparql.dbacademic.tech) 