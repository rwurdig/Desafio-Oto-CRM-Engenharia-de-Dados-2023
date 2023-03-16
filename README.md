# Desafio Oto CRM // Engenharia de Dados - 2023
Teste de Seleção para a vaga de Engenheiro de Dados

# O QUE DEVE SER FEITO NO TESTE 1

// SOBRE O TESTE

Avaliar a capacidade técnica, crítica e raciocínio lógico do candidato
ao construir uma aplicação e interface de usuário para resolução do
problema proposto.
Receita, frequência e valor
A tabela abaixo representa as compras de alguns clientes.

![image](https://user-images.githubusercontent.com/72509000/224693499-b9fcae5f-8d35-4843-8d14-0350ffa7ab80.png)

Construa uma consulta (SQL) que calcule as métricas de RFV de cada um dos
clientes:

● Recência = Tempo desde a última compra (dias)

● Frequência = Quantidade de compras

● Valor = Valor total em compras

Você deverá implementar o fluxo de tratamento de dado

# O QUE DEVE SER FEITO NO TESTE 3

Você deverá implementar o fluxo de tratamento de dados descrito
abaixo, utilizando o dataset a seguir como base:
https://oto-public.s3.amazonaws.com/natal2021.zip

Sua tarefa:

Com o objetivo de realizar uma campanha especial de final de ano,
recebemos o arquivo natal2021.csv do cliente. Você recebeu o
desafio de realizar a limpeza deste arquivo CSV para que possamos
posteriormente importá-lo em nosso banco de dados. Pensando em
um cenário no qual o arquivo CSV seja muito maior e não entre na
memória de uma só vez, temos os seguintes problemas para serem
resolvidos:

1. Identificar o encoding do arquivo;

2. Processar o arquivo de 1000 em 1000 linhas;

3. Remover os espaços das colunas. Ex. ' Porto Alegre ' -> 'Porto Alegre';

4. Criar uma coluna CITY_ASCII no arquivo, a qual deve ser construída
com base na coluna CITY. Esta coluna não pode conter acentos,
minúsculas e caracteres especiais. Apenas letras, números e hífen são
permitidos. Ex. 'São Paulo - abç' -> 'SAO PAULO - ABC'

5. Remover os caracteres não numéricos da coluna PHONE;

6. Salvar o arquivo .csv com a nova coluna em UTF-8;


# O QUE DEVE SER FEITO NO TESTE 2

# Integração e-commerce

Um cliente gostaria de integrar os dados de seu e-commerce com nossa
plataforma. Ele utiliza Vtex. Como você desenharia a arquitetura desta
integração? Quais sistemas, fluxos e pipelines de dados você criaria?

Considere que serão integrados os seguintes dados:

● Catálogo de produtos

● Pedidos realizados

● Cadastro de clientes

Observe que você deve apenas dissertar sobre a arquitetura, e não codificar.

# O QUE SERÁ AVALIADO ?

● Funcionalidade: se atinge o objetivo esperado dentro das
limitações impostas.

● Legibilidade do código: será verificado se está fácil de ser lido e
entendido, com nomes das funções e variáveis de acordo com a sua
funcionalidade.

● Documentação, comentários e reaproveitamento de código.

● Organização na estrutura de arquivos.

● Boas práticas de desenvolvimento.

● Tempo de entrega.

# ENTREGAS NECESSÁRIAS

● Você deve salvar o código fonte necessário em um repositório
Git da sua escolha.

● Enviar para o e-mail:, renata.rehm@otocrm.com.br,
everton.cunha@otocrm.com.br, tobias.jacoby@otocrm.com.br
