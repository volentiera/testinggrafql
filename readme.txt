graphql instructions


query getAll{
  getAll{
    id,
    tittle
  }
}
mutation create{
  create(data:{
    tittle: "algoooo",
    desc: "alguito",
    img: "http://hola.com"
    price: "15000"
  }){
    id
  }
}
mutation delete{
  delete(id:"<id>")
}

mutation update{
  update(
    id:"<id>",
    data:{
    	tittle: "holaaa"
  	}) {
    id
  }
}
