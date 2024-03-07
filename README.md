# Analise-de-Dados
## Projeto de Análise de Dados visando minimizar o turnover de uma empresa.
Projeto de Análise de Dados que visa minimizar o turnover de uma empresa. Os dados foram retirados da base da Escola Preditiva.ai 

O Turnover é a taxa de rotatividade de colaboradores de uma empresa. Ele serve para demonstrar como está o clima organizacional e verificar se existem problemas internos na corporação. 
Essa rotatividade pode ter diferentes motivos e consequências. São muitas as questões que fazem um funcionário deixar a empresa, entre eles: Melhores oportunidades, clima organizacional ruim, chefes inadequados, baixo equilíbrio entre vida pessoal e profissional, entre outros. Seja por parte do funcionário ou da empresa, o turnover costuma ser prejudicial ao negócio. 
Dentre os principais impactos temos:
•	Clima Organizacional, Produtividade e Custos Financeiros:
A constante substituição de funcionários pode gerar desgaste e instabilidade, prejudicando a motivação e a coesão da equipe. 
A saída frequente de colaboradores exige que a empresa gaste tempo e recursos na recontratação e treinamento de novos talentos.

•	Imagem da Empresa e Employer Branding:
Uma alta rotatividade pode ser percebida como um sinal de instabilidade ou má gestão. Isso afeta o employer branding, ou seja, a capacidade da empresa de atrair e reter talentos. Candidatos em potencial podem evitar empresas com histórico de alta rotatividade.
•	Qualidade do Atendimento ao Cliente:
A substituição de funcionários pode levar a falhas e atrasos nos processos internos, afetando a qualidade do atendimento aos clientes.
Portanto, é essencial que as organizações adotem estratégias para reduzir o turnover e promover a retenção de talentos.

### Problema de Negócio e Dados
Para tentar entender quais as características que fazem um funcionário ficar ou deixar uma empresa de Tecnologia, o RH da empresa catalogou informações de 1470 funcionários que deixaram ou permaneceram na companhia no último ano. 
O resultado desse levantamento gerou 19 possíveis fatores que explicam o comportamento do turnover. Os fatores estão na tabela de Metadados abaixo:

![Captura de tela 2024-03-07 180017](https://github.com/marciacf/Analise-de-Dados/assets/102993177/42d32421-389f-495b-9ddf-e4206ff2b95b)
Com base nisso, o RH encomendou um estudo para responder a seguinte pergunta:
#### Quais políticas/fatores da empresa deveriam mudar de forma a minimizar o turnover?
Os dados deste trabalho foram retirados da base da Escola Preditiva.ai .

### Metodologia
Foi feita uma análise bidimensional entre a variável turnover e a demais variáveis.
Dentre as análises feitas, foram utilizados gráficos box plot entre a variável turnover (Variável Qualitativa) e cada umas das variáveis quantitativas. Isso permite avaliar a média e os percentis.
Já entre a variável turnover e as variáveis qualitativas foram analisadas as frequências absolutas e relativas.
A técnica de correlação Information Value (IV) foi inserida para identificar quais variáveis tem maior impacto no turnover dos funcionários.
O Information Value (IV) é usado para avaliar o poder preditivo de um determinado recurso em um conjunto de dados. O que nos permite selecionar as variáveis mais relevantes para as presentes análises.
Os valores de IV são avaliados conforme a tabela abaixo:

![Captura de tela 2024-03-07 180259](https://github.com/marciacf/Analise-de-Dados/assets/102993177/84361d84-82e9-4d48-89bc-0dd7314ddcf2)

### Resultados
A taxa de turnover atual (% pessoas que saíram / total de funcionários) foi de 16%.

![Captura de tela 2024-03-07 180432](https://github.com/marciacf/Analise-de-Dados/assets/102993177/7894b8f5-6622-49a8-a1d8-bd56899c86da)

Os fatores que tiveram os maiores valores de IV foram:

![Captura de tela 2024-03-07 180532](https://github.com/marciacf/Analise-de-Dados/assets/102993177/9b844e9f-66de-48d7-866a-c070c55dfb00)

#### Funcionários que fazem hora extra:


![Captura de tela 2024-03-07 180647](https://github.com/marciacf/Analise-de-Dados/assets/102993177/1e03ff42-5b30-495c-a783-ab1b9aa30809)




![Captura de Tela (52)](https://github.com/marciacf/Analise-de-Dados/assets/102993177/98515687-aa00-4051-8f77-b90ec3291887)






