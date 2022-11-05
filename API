var express = require ("express")
var app = express()

var materials = [
  {
    name:"dados",
    id:"01"
    },
  {
    name:"status",
    id:"02"
    },
  {
    name:"state",
    id:"03"
}
]

app.get("/",(req,res)=>{
 res.send("Página Inicial")
})

app.get("/all",(req,res)=>{
res.json(materials)
})
    
app.get("/materials/:id",(req,res)=>{
materials.forEach((element)=>{

  if (req.params.id == element.id) {
     item = element
  }
  
})
  
  res.json(item)
})

app.listen(3000,()=>{
  console.log("Servidor Rodando...")
})

