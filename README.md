<h1> Hey! Im Luis Flores ⚫ </h1>

<p><em>Node.js Developer</em></p>

### Who am I? 

```javascript
const express = require('express')
const app = express()
app.use(express.json())

app.get('/me',(req,res,next) => {
  res.status(200).json({
    status: 'success'
    data: {
      name: 'Luis Daniel Flores Velázquez',
      aka: 'Naoko',
      languages: ['JavaScript'],
      tools: ['Node.js', 'Serverless', 'MongoDB', 'AWS']
    }
  })
})

app.listen(9000, () => console.log('Server ready'))
```
