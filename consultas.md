# Consultas simples

## Igualdade

Realizar consultas baseadas em um valor específico para um campo:

db.usuarios.find({ “endereco.cidade”: "São Paulo" })

## Operadores Lógicos

Realizar consultas baseadas em um valor específico para um campo.​

$and​

$or​

$not


## Operadores Comparação (antes do : é como é utilizado no MongoDB e após no JS)

$eq: ==​

$ne: !=​

$gt: >​

$gte: >=​

$lt: <​

$lte: <=​

$in: []​

$nin: []

## Projeções

Definir quais campos devem ser retornados em uma consulta.

## Ordenação

Ordenar os resultados de uma consulta com base em um ou mais campos.

## Limitação

Limitar o número de documentos retornados em uma consulta.

## Paginação (skip -> quanto registros serão ignorados, limit -> quantos serão mostrados)

db.usuarios.find().skip(10).limit(5)







