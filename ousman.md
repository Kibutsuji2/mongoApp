
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
