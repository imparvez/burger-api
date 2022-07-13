# burger-api

### Create fake API with json-server package

##### First thing you need to install json-server package
- `npm install -g json-server`

##### Now you need to create a .json file with all the data which can act as database.
- For example: `db.json`
- Create a JSON structure with required information.

##### You can now run a following command on your local to host you DB.
- `json-server --watch db.json`

This will host your local json file on some random port from where you can access json data.