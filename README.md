# Analise-de-Dados_Projeto_Turnover
## Projeto de Análise de Dados visando minimizar o turnover de uma empresa.
Projeto de Análise de Dados que visa minimizar o turnover de uma empresa. Os dados foram retirados da base da Escola Preditiva.ai 

O Turnover é a taxa de rotatividade de colaboradores de uma empresa. Ele serve para demonstrar como está o clima organizacional e verificar se existem problemas internos na corporação. 

Essa rotatividade pode ter diferentes motivos e consequências. São muitas as questões que fazem um funcionário deixar a empresa, entre eles: Melhores oportunidades, clima organizacional ruim, chefes inadequados, baixo equilíbrio entre vida pessoal e profissional, entre outros. Seja por parte do funcionário ou da empresa, o turnover costuma ser prejudicial ao negócio. 
Dentre os principais impactos temos:
  -	Clima Organizacional, Produtividade e Custos Financeiros:
    
A constante substituição de funcionários pode gerar desgaste e instabilidade, prejudicando a motivação e a coesão da equipe. 
A saída frequente de colaboradores exige que a empresa gaste tempo e recursos na recontratação e treinamento de novos talentos.

  -	Imagem da Empresa e Employer Branding:
    
Uma alta rotatividade pode ser percebida como um sinal de instabilidade ou má gestão. Isso afeta o employer branding, ou seja, a capacidade da empresa de atrair e reter talentos. Candidatos em potencial podem evitar empresas com histórico de alta rotatividade.
  -	Qualidade do Atendimento ao Cliente:
    
A substituição de funcionários pode levar a falhas e atrasos nos processos internos, afetando a qualidade do atendimento aos clientes.

Portanto, é essencial que as organizações adotem estratégias para reduzir o turnover e promover a retenção de talentos.

### Problema de Negócio e Dados
Para tentar entender quais as características que fazem um funcionário ficar ou deixar uma empresa de Tecnologia, o RH da empresa catalogou informações de 1470 funcionários que deixaram ou permaneceram na companhia no último ano. 
O resultado desse levantamento gerou 19 possíveis fatores que explicam o comportamento do turnover. Os fatores estão na tabela de Metadados abaixo:

![Captura de tela 2024-03-08 083026](https://github.com/marciacf/Analise-de-Dados/assets/102993177/07dd34a4-8c89-4d05-94d3-2da9d9f26b39)
Com base nisso, o RH encomendou um estudo para responder a seguinte pergunta:
#### _Quais políticas/fatores da empresa deveriam mudar de forma a minimizar o turnover?_
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

A taxa de turnover dos funcionários que fazem hora extra foi de 31%.
Dos funcionários que saíram da empresa, 54% deles faziam hora extra.

#### Salários dos Funcionários:

![Captura de tela 2024-03-08 083342](https://github.com/marciacf/Analise-de-Dados/assets/102993177/df9b6d9e-24d4-49b2-a4a7-a5929eb00d81)

50% dos funcionários que saíram da empresa tem salários entre 2370 e 5955 reais.
50% dos funcionários que estão da empresa tem salários entre 3211 e 8836 reais.
Com isso a média dos salários de quem sai da empresa é cerca de 30% menor.

#### Quantidade de ações da empresa que os funcionários possuem:

![Captura de tela 2024-03-08 083600](https://github.com/marciacf/Analise-de-Dados/assets/102993177/8512c896-8ea4-4bab-9c0f-41a2c43d9221)

65% dos funcionários que saíram da empresa não tinham nenhuma ação.
61% dos funcionários que estão na empresa tem pelo menos uma ação.

#### Tempo de carreira:

![Captura de tela 2024-03-08 083844](https://github.com/marciacf/Analise-de-Dados/assets/102993177/2891d26b-0ee6-43a5-a219-f2c37be04449)

50% dos funcionários que saíram da empresa tem tempo de carreira entre 3 e 10 anos.
50% dos funcionários que estão na empresa tem tempo de carreira entre 6 e 16 anos.
O tempo de carreira de quem sai da empresa é cerca de 31% menor.

#### Tempo de empresa:

![Captura de tela 2024-03-08 084543](https://github.com/marciacf/Analise-de-Dados/assets/102993177/7f8c43a9-b6b7-4165-b71c-00c04eee6885)
![Captura de tela 2024-03-08 084622](https://github.com/marciacf/Analise-de-Dados/assets/102993177/06be9ede-4afa-49c4-a47c-9b9f7eba1ed1)

50% dos funcionários que saíram tem tempo de empresa entre 1 e 7 anos.
50% dos funcionários que estão na empresa tem tempo de empresa entre 3 e 10 anos.
O tempo de empresa de quem sai da empresa é cerca de 30% menor.

#### Estado Civil:

![Captura de tela 2024-03-08 084847](https://github.com/marciacf/Analise-de-Dados/assets/102993177/4408f99e-bdce-4da8-812b-b6c52c5414ed)

51% dos funcionários que saíram da empresa eram solteiros. 
28% dos funcionários que estão na empresa são solteiros. 

#### PRODUTO – DASHBOARD DE CONTROLE 

Foi desenvolvido um Dashboard utilizando o software PowerBI, que contém os principais indicadores 
associados ao turnover. Esse produto pode auxiliar os gestores com o controle e monitoramento da equipe. 
Segue a imagem do dashboard com o resumo dos resultados: 

![Captura de Tela (52)](https://github.com/marciacf/Analise-de-Dados/assets/102993177/98515687-aa00-4051-8f77-b90ec3291887)


### Considerações finais 

Através do cálculo do Information Value (IV), foi possível detectar os fatores que mais impactaram o turnover 
da empresa, que foram: 
  - Hora Extra 
  - Salário 
  - Quantidade de ações da empresa 
  - Tempo de carreira 
  - Tempo de empresa 


Dessa forma, foi feita uma análise mais detalhada, a fim de entender como esses fatores impactam no 
turnover, concluímos que: 
  - Dos funcionários que saíram da empresa, 54% deles faziam hora extra. É recomendado como plano 
de ação que a empresa avalie as políticas associadas a hora extra. 
  - A média dos salários de quem sai da empresa é cerca de 30% menor. É importante que a empresa 
faça uma análise de mercado referente a salários de cargos variados, avaliando empresas de mesmo 
segmento. 
  - Dos funcionários que saíram da empresa, 65% não possuem nenhuma ação da empresa. Como 
plano de ação, a empresa deve avaliar a política de distribuição de ações e gatilhos associados a 
performance dos funcionários. 
  - O tempo de carreira dos funcionários que saíram da empresa é cerca de 31% menor, em relação aos 
funcionários que permaneceram na empresa. 
  - Os funcionários que saíram da corporação, tinham Tempo de empresa cerca de 30% menor em 
relação ao Tempo de empresa dos funcionários que permaneceram. É necessário que a empresa 
reestruture o plano de carreira, oferecendo oportunidades de crescimento e progressão de carreira. 
Outro ponto, seria avaliar como esta o ambiente corporativo e o clima organizacional da empresa. 

O turnover não é apenas uma métrica de RH, ele tem repercussões na operação, na cultura organizacional e 
na saúde financeira da empresa. Portanto, é essencial que as organizações adotem estratégias para reduzir o 
turnover e promover a retenção de talentos. Dado que cada empresa é única, é importante adaptar essas 
estratégias à realidade e às necessidades específicas da organização.



