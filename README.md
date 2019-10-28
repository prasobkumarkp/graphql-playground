# graphql-graphiql-tut

graph tutorial using graphiql
https://www.linkedin.com/learning/graphql-essential-training

# Sample data
## mutation stage 0
mutation{
createFriend(input:{
firstName:"Prasob"
lastName:"kumar"
gender:MALE
age:29
email:"em@me.com"
contacts:[
{firstName:"Sam" lastName:"winchester"}
{firstName:"Dean" lastName:"Winchester"}
]
})
{
id
firstName
contacts{
firstName
lastName
}
}
}

## query stage 0
query{
getFriend(id:"3a89076c9a51edd34614"){
firstName
contacts{
firstName
}
}
}

# mongodb

mongod --dbpath data/db --port 8081
