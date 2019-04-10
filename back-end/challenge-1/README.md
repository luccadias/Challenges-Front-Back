### Requisitos:
* Cadastre-se no [Mlab](https://mlab.com/) (MongoDB na nuvem), crie um Database User e uma collection, assista esse vídeo se tiver alguma dúvida: [mLab - Hospede seu banco MongoDB de graça na nuvem!](https://www.youtube.com/watch?v=Xodof0NDIbk)
* Para desenvolvimento com **NodeJS** utilize a lib [MongoDB - NodeJS](https://www.npmjs.com/package/mongodb)
* Para desenvolvimento com **Python** utilize o [PyMongo](https://api.mongodb.com/python/current/)

### Objetivo:
* Crie uma rota **POST**  ``/registerUser`` para cadastrar dados do usuario no banco de dados (Mlab), o formato deve ser parecido com esse:
```json
{
  "name":"",
  "age": 0,
  "email": ""
}
```
* Crie uma rota **GET** ``/users``para recuperar todos os usuarios que estão cadastrados no banco de dados.

### Dicas:
* Para testar as requisições você pode usar o [Postman](https://www.getpostman.com/).
* Para não precisar ficar matando o servidor NodeJS toda hora, utilize o [NodeMon](https://nodemon.io/).
* Para desenvolver as chamadas, utilize [Flask](http://flask.pocoo.org/) para o **Python** e [Express](https://expressjs.com/pt-br/) para o **NodeJs**

##### That`s it