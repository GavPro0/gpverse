# gpverse-db

## Install
```sh
# Enter DB Module.
cd gpverse-db

# Install dependencies. 
npm i

# Run NPM Scripts.
npm run lint

# Run NPM Scripts, detect and fix errors.
npm run lint -- --fix
```

## Usage
```js
const setupDatabase = require('gpverse-db')

setupDatabase(config).then(db => {
  const { Agent, Metric} = db
  
}).catch(err => console.error(err))
```
