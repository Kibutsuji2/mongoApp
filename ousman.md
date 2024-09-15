
curl -X POST -H "Content-Type: application/json" -d '{"name": "John", "age": "25"}' http://localhost:3000/api/post

history
OUSMANE Mohamed Sadjad
12:31
https://github.com/nvm-sh/nvm?tab=readme-ov-file#installing-and-updating

12:34
source ~/.zshrc
OUSMANE Mohamed Sadjad
13:19
mongodb://username:password@localhost:27017/?authSource=admin
Vous
13:39
commande de curl
Pointez sur un message pour l'épingler
keep
OUSMANE Mohamed Sadjad
13:41
curl http://localhost:port/api/getAll
OUSMANE Mohamed Sadjad
13:45
curl -X POST http://localhost:3000/api/post -d '{
  "name": "John Doe",
  "age": 30
}'


mongoose
  .connect(db_url, {
    useNewUrlParser: true,
    useUnifiedTopology: true,
    dbName: 'MyDatabaseName',
  })
  .then(() => {
    console.log('Connected to the Database.');
  })
  .catch(err => console.error(err));


  curl -X GET -H "Content-Type: application/json" http://localhost:3000/api/getAll // tout afficher

curl -X GET -H "Content-Type: application/json" http://localhost:3000/api/getOne/66cb46a7e0c8e9b02477e41c //afficher par son id

curl -X POST -H "Content-Type: application/json" -d '{"name": "wille", "age": "22"}' http://localhost:3000/api/post // inserer les donnee

curl -X PATCH -H "Content-Type: application/json" -d '{"name": "modi", "age": "21"}' http://localhost:3000/api/update/66cb46a7e0c8e9b02477e41c //pour faire le update

curl -X DELETE -H "Content-Type: application/json" http://localhost:3000/api/delete/66cb46a7e0c8e9b02477e41c // Suppressiong
