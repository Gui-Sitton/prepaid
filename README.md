# Qual.e.o.Melhor.Plano
Sou aluno da Practicum no curso de Ciência de Dados, estou divulgando projetos que desenvolvi para meu portifólio. Este é o quarto projeto.

Neste projeto trabalho como analista para a empresa de telecomunicações Megaline. A empresa oferece aos seus cliente planos pré-pagos, Surf e Ultimate. O departamento comercial quer saber quais dos planos dão mais receita para ajustar o orçamento de publicidade.
Você vai realizar uma primeira análise dos planos baseados em uma pequena seleção de clientes. Você terá dados de 500 clientes da Megaline: que clientes são, de onde eles são, qual plano usam, o número de chamadas que eles fizeram e mensagens que eles enviaram em 2018. O seu trabalho é analisar o comportamento dos clientes e determinar quais planos pré-pagos dão mais receita.

**Descrição dos planos**

Perceba: A Megaline arredonda segundos para minutos, e megabytes para gigabytes. Para chamadas, cada chamada individual é arredondada para cima: mesmo se uma chamada tenha durado apenas um segundo, será contado como um minuto. Para trafego de web, sessões individuais de web não são arredondadas para cima. Ao invés disso, o total do mês é arredondado para cima. Se alguém usar 1025 megabytes esse mês, eles serão cobrados por 2 gigabytes.

**Surf**

Preço mensal: $20
500 minutos mensais, 50 mensagens de texto, e 15 GB de dados
Depois de exceder os limites do pacote:
1 minuto: 3 centavos
1 mensagem de texto: 3 centavos
1 GB de dados: $10

**Ultimate**

Preço mensal: $70
3000 minutos mensais, 1000 mensagens de texto, e 30 GB de dados
Depois de exceder os limites do pacote:
1 minuto: 1 centavo
1 mensagem de texto: 1 centavo
1 GB de dados: $7

**Teste as hipóteses**
* A receita média dos usuários dos planos Ultimate e Surf são diferentes.
* A receita média dos usuários da área de NY-NJ é diferente dos usuários de outras regiões.

*Conclusão**

O plano surf por ter um limite mais baixo muitas pessoas pagam um valor extra pelo uso, superando o valor do plano ultimate muitas vezes, trazendo assim mais dinheiro para a empresa. Já o ultimate não, todos seus usuários pagam 70 dólares. Não podemos afirmar que a receita da região de NY-NJ é igual as demais, sua média é um pouco a baixo da média das demais.
