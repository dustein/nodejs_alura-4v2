
npx sequelize-cli init
(npx serve para instalar os rerusos que ja estao locais na maquina)
moveu as pastas criadas da raiz pra dentro da pasta api que criamos pro projeto. Por isso informar a nova localizacao criando o arquivo .sequelizerc

mysql -u 'root' -p
mysql> show databaes;
create database escola_ingles;
configurar o config.json com os dados de acesso ao banco de dados
Na pasta models, o index.js gerencia os modelos

npx sequelize-cli model:create --name Pessoas --attributes nome:string,ativo:boolean,email:string,role:string (vai criar um novo modelo, as pastas migrations, e o arquivo pessoas.js no models)

aula 2 finalizada (criando modelos)