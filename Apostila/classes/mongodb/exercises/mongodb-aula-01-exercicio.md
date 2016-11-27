#MongoDb - Aula 01 - Exercício
autor:Everton Messias

##Importando os restaurantes
  ```
  messi@everton-mortal:~/Mongo$ mongoimport --db be-mean --collection restaurantes restaurantes.json_
  2016-11-26T22:58:20.517-0200	connected to: localhost
  2016-11-26T22:58:22.023-0200	imported 25359 documents
  ```
##Contando os restaurantes
  ```
  use be-mean
  db.restaurantes.find({}).count()
  25359
  ```
