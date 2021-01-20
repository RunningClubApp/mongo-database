# Use
Import as a git submodule

# Config file
put ``` db.config.js ``` in the folder containing this package.

for production:
```javascript
module.exports = {
  user: <username>,
  pwd: <password>,
  url: <mongo host>,
  db: <database name>
}
```

otherwise:
```javascript
module.exports = {
  url: <mongo host>,
  port: <port>,
  db: <database name>
}
```