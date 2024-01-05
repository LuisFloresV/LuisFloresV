<h1> Hey there! Im Luis Flores </h1>

<p><em>Node.js Backend Developer</em></p>

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
      tools: ['Node.js', 'Express.js', 'Jest', 'MongoDB', 'AWS']
    }
  })
})

app.listen(9000, () => console.log('Server ready ✨'))
```
![My Github stats](https://github-readme-stats.vercel.app/api?username=LuisFloresV&show_icons=true&hide_border=true&theme=dark)   


