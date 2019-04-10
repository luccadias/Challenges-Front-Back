 
### Objetivos: 
 * Criar uma página que lista todos os post`s da API [GoRest](https://gorest.co.in/) 
 * Criar um Search Bar para buscar os post`s por nome do usuario
 * Siga o Design para desenvolvimento do style
 
### Dicas: 
 * Utilize [FontAwesome](fontawesome.com) para personalizar os Icones.
 * Use [Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) para facilitar a leitura do style 

 ### API [GoRest](https://gorest.co.in/)
  - Para essa etapa utilize Apenas essas rotas:
``/public-api/users``
``/public-api/posts``

  - O ```GET``` de Posts não retorna a imagem do usuario, para isso você vai precisar buscar um usuario especifico na rota ``/public-api/users/$IdUser``
  
  - Não esqueça de se cadastrar no site para pegar a autorização da API. 
  Obs: Token de autorização precisa colocar no header.

### Design da aplicação:
```css
  font-family: AppleGothic,

  # Title NavBar
  color: #646464,
  placeholder: rgba(100, 100, 100, 0.6)

  # Title Post
  color: #646464,

  # Text Post
  color: #646464,
  opaticy: 0.8
```
![alt text](SocialPosts.png)
