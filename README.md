#Install package 

Run cmd with 
```sh
npm i word2pdf
```
 or 
 ```sh
 yarn add word2pdf
 ```

#Use

Example

```javascript
const word2pdf = require('word2pdf');
const fs = require('fs');

word2pdf(sourcePath, outputPath).then(() => res.send("success"), err => res.send(err));
```

