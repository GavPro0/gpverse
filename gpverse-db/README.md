# gpverse-db

## Usage

``` js
const setupDatabase = require('gpverse-db')

setupDatabase(config).then(db => {
  const { Agent, Metric} = db
  
}).catch(err => console.error(err))
```